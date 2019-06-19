# UID-Masking-Angularjs-Directive

This angularjs directive is used to mask the entered aadhaar number and mobile number with user customized mask length and checks verhoeff validation

### Importing Library
```
 var app = angular.module('MyApp', [
        'input_masking'
    ]);
```
### Usage

#### For masking complete aadhaar number 
```
<input maxlength="12" class="form-control" uid-input-model="input_data" />

You can get unmasked aadhaar number from $scope.input_data variable in Controller.

```

#### For masking upto certain length 
```
<input maxlength="12" class="form-control" uid-input-model="input_data" mask-length="5" />

In the above html input number is masked upto specified mask-length attribute
You can get unmasked aadhaar number from $scope.input_data variable in Controller.

```


#### For masking complete mobile number 
```
<input maxlength="10" class="form-control" mobile-input-model="input_data" />

You can get unmasked aadhaar number from $scope.input_data variable in Controller.

```

#### For masking upto certain length 
```
<input maxlength="12" class="form-control" mobile-input-model="input_data" mask-length="5" />

In the above html input number is masked upto specified mask-length attribute
You can get unmasked aadhaar number from $scope.input_data variable in Controller.

```
#### For show/hide input  
```
<input maxlength="10" class="form-control" uid-input-model="input_data" uid-input-mask="mask_flag" mask-length="5"/>
<input maxlength="10" class="form-control" mobile-input-model="input_data" mobile-input-mask="mask_flag" mask-length="5"/>
You can get unmasked number making mask_flag toggle.

```

### Support or Contact
For any issues in the code please raise an issue or mail me for any other information. 

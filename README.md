# password-tag

### CDN
        https://unpkg.com/password-validation-tag@1.0.0/password-component-d.js

  ## How to use password-valid-tag

- Add above cdn link in the script tag, and place the script tag at the bottom of the body in your html page
- Now you can use `<password-valid-tag></password-valid-tag>` in your page
- by default it takes 1 uppercase, 1 lowercase, 1 special, 1 number, mininimum 4 char and max 50 
- Simply styles can be added in component's js page as well as in different styles page, **note** reg_Password is the name of inputs id 


## Attributes

* upperCase: U
* lowerCase: L
* special: S
* numbers: N
* min-length: Min
* max-length: Max

#### Ex:
        <password-valid-tag U="2" L="3"> </password-valid-tag>  // this tag will take two uppercase and three lowercase characters

**Note:** In some case, in form while submitting add onSubmit attribute for calling isValidation(this) for 
confirming the validation, this case will arise when this tag will be added in html dynamically(from javascript code).

**Note:** Always add the cdn link below bottom of the body tag
![Screenshot from 2022-09-09 16-11-24](https://user-images.githubusercontent.com/65856669/189332584-055e1bb3-b2eb-4201-bef1-e99a332d2f17.png)


## Output:
![Screenshot from 2022-09-09 16-27-40](https://user-images.githubusercontent.com/65856669/189335401-8511eafd-9275-4729-9fef-b61fd4188973.png)


**Issue**: 
If writing logic for "New password" & "re-enter password", It is recommended to write "re-enter password" code by yourself.
This issue will get resolve some day.


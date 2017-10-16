# useless-user-results
These are the results of the useless user testing. The objective of the test was to compare the performance of Aurelia, Angular 4 and React.

### [Web Server](https://github.com/JeffreyRiggle/useless-user-gen)
### [Aurelia](https://github.com/JeffreyRiggle/useless-user-aurelia)
### [Angular](https://github.com/JeffreyRiggle/useless-user-angular)
### [React](https://github.com/JeffreyRiggle/useless-user-react)

# Conducting the test.
In order to conduct the test an instance of the useless-user-gen was started on my machine. Once this was started I started a web server hosting either the Aurelia, Angular 4 or React application.

Once this was done I created 1000 users 3 times, Updated 1000 users 3 times and cleared out the users.

# Results from the test

## Create users
|Framework|First    |Second   |Third    |Average  |
|---------|---------|---------|---------|---------|
|Angular  |465.5ms  |388.2ms  |426.5ms  |410.1ms  |
|Aurelia  |331.0ms  |301.2ms  |370.3ms  |334.2ms  |
|React    |320.2ms  |315.5ms  |334.2ms  |323.3ms  |

## Update users
|Framework|First    |Second   |Third    |Average  |
|---------|---------|---------|---------|---------|
|Angular  |648.6ms  |454.8ms  |476.2ms  |526.5ms  |
|Aurelia  |614.2ms  |448.0ms  |461.7ms  |508.0ms  |
|React    |279.4ms  |220.9ms  |219.5ms  |239.9ms  |

## Clear users
|Framework|Time     |
|---------|---------|
|Angular  |274.5ms  |
|Aurelia  |171.1ms  |
|React    |147.5ms  |

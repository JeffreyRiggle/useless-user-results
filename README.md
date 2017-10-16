# What is this?
These are the results of the useless user testing. The objective of the test was to compare the performance of Aurelia, Angular 4 and React.

### [Web Server](https://github.com/JeffreyRiggle/useless-user-gen)
### [Aurelia](https://github.com/JeffreyRiggle/useless-user-aurelia)
### [Angular](https://github.com/JeffreyRiggle/useless-user-angular)
### [React](https://github.com/JeffreyRiggle/useless-user-react)

# Conducting the test
In order to conduct the test follow these steps.

1. Start the [web server](https://github.com/JeffreyRiggle/useless-user-gen) on a machine.
2. On the same machine start either the [Angular](https://github.com/JeffreyRiggle/useless-user-angular), [Aurelia](https://github.com/JeffreyRiggle/useless-user-aurelia) or [React](https://github.com/JeffreyRiggle/useless-user-react) web server.
3. On the same machine navigate to the web site.
4. Open developer tools.
5. Start profiling.
6. Enter 1000 and press create 3 times waiting 2 seconds between each press.
7. Stop profiling.
8. Start profiling.
9. Press update 3 times waiting 2 seconds between each press.
10. Stop profiling.
11. Start profiling.
12. Press Clear.
13. Stop profiling.

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

# Additional Details

## File Size

### Angular

|File                   |size                   |
|-----------------------|-----------------------|
|index.html             |1kb                    |
|inline.bundle.js       |6kb                    |
|inline.bundle.js.map   |6kb                    |
|main.bundle.js         |25kb                   |
|main.bundle.map.js     |24kb                   |
|polyfills.bundle.js    |212kb                  |
|polyfills.bundle.js.map|253kb                  |
|styles.bundle.js       |12kb                   |
|styles.bundle.js.map   |15kb                   |
|vendor.bundle.js       |2,199kb                 |
|vendor.bundle.js.map   |2,748kb                 |

### Aurelia

|File                   |size                   |
|-----------------------|-----------------------|
|index.html             |1kb                    |
|main.js                |2,284kb                |
|styles.css             |3kb                    |

### React

|File                   |size                   |
|-----------------------|-----------------------|
|index.html             |1kb                    |
|main.js                |2,143kb                |
|styles.css             |3kb                    |

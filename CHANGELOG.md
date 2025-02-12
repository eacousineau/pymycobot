# 2021

## 6.24

- release v2.5.3
- sync with Atom3.1

## 6.10

- release v2.5.1
- improved parameter checking.
- new class `MycobotCommandGenerator` that generate binary real command.
- can import needed class from `pymycobot`, like:
  ```python
  from pymycobot import Mycobot, Angle, Coord, MycobotCommandGenerator
  ```

## 5.27

- release v2.4.2
- fixed `set_pwm_output()`

## 5.24

- update demo.

## 4.27

- release v2.4.0
- set_free_mode -> release_all_servos
- Add new port:
  - is_controller_connected
  - set_servo_data
  - get_servo_data
  - set_servo_calibration
  - set_basic_output
- Update API document.

## 4.25

- release v2.3.6
- fix focus_servo error

## 4.20

- release v2.3.5
- fix v2.3.4 install error

## 4.19

- release **v2.3.4**
- update debug mode

## 4.2

- relase **v2.3.3**
- fix bug.

## 3.29

- release **v2.3.1**
- fix error bug
- add new method `set_encoder`, `get_encoder`, `set_encoders`

## 3.26

- release **v2.3**
- fix `is_in_position()`
- refactor process method
- some methods can be chained
- add new methods to control pump
- change `set_led_color(rgb:str)` -> `set_color(r:int, g:int, b:in)`

## 3.12

added more test file.

## 2.5

relase **v2.2.0**

- add new method for girpper and IO.

## 1.25

release **v2.1.2**

- refactor pymycobot
- add Error class

## 1.20

`v1.0.6` fix get_coords() error.

relase v2.0.0

## 1.16

Upload to server, can use `pip` to installation now.

## 1.9

Fix the API problem that `is_moving()` and other methods of mycobot cannot be used.

## 1.8

Python API add new methods:

- `jog_angle()`
- `jog_coord()`
- `jog_stop()`

# 2020

## 12.30

Adding usage documents to Python API.

## 12.29

Python API supports python2.7

Modify the serial port to manual setting, support the use of window.

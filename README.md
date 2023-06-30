Sequencer


The Sequencer provides functionality to sequence events, such as powering on and off. It was built with amp racks in mind, but can be used to sequence any list of actions that need to happen in order, with a set delay between.


Controls:

-On/Off: (Trigger) Immediately start the sequence, turning each tap either on or off. These controls will not respond if a sequence is already running.

-Abort: (Trigger) Immediately stops the currently running sequence. All states are left as they are the moment the sequence is aborted. On/Off controls become available again.

-Running: (Toggle) Led is on when a sequence is running and off when it isn't.

-Delay (S): (Knob) The numer of seconds the sequence will wait before moving on to the next tap. The control can be changed while the sequence is running, however, the actual delay time will not change until the sequence stops. Range is .001-60. Minimum value can be used to change all taps simultaneously.

-Reverse Off Order: If this is turned on when the 'off' sequence is started, the sequence will run from the bottom up. Any 'on' sequence wil always run from the top down regardless.

-Taps: Each tap includes 2 trigger buttons and a state, along with a pin out for each. When the sequence turns a tap on or off, the associated trigger fires, and the state goes to the associated logic state. When a trigger button is pushed, the state is set to the associated logic state, and when the state is changed, the associated trigger is fired. Each tap also includes a bypass button. When a bypass is turned on, that tap will not change within a sequence.

1.1 Update:
  Functionality added:
    'Reverse Off Order' option, tap-level bypass

How to get in touch:
If you need help, or would like to make a request, please feel free to contact me using the communities messaging system, or my email address: zanderpm@gmail.com

Also, if you have plugin-building experience and have suggestions as to how I can improve my design, code, or anything else, please use the contact info above. I'd really appreciate any advice you have to share.

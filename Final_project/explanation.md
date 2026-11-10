* Started with the traffic light green -> yellow -> red sequence from previous lab, and the 10 to zero counter from different previous lab
* duplicated the traffic light setup
* Created an FSM that went through the light sequence properly
* added button input to FSM and crossing light output state
* modified the FSM to have an additional state that is triggered only when the button has been pressed and the lights are in the "all red" state
* used a multiplexer to switch from the 3 second count to the 10 second count if button is triggered
* locked the button input 'on' with a flip flop until the countdown reaches zero


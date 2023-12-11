7.4 Controlling the Rectifiers You can manually control the operating status of the rectifiers.

Table 7-1 Descriptions of the Rectifier Parameters

S.N. Parameter           Default Value         Value Range and Description 
1   Soft Start Inter.    0 s 0                  s-128 s 
                                                It refers to the starting time interval (s) of the rectifiers. 
												                        The system starts the rectifiers one after another based on their CAN address.

2   Out. High Off. V     61.0 V                 56.5 V-62.0 V
                                                It refers to the output voltage threshold of the rectifiers. 
												                        If the output voltage is higher than the threshold, the rectifier stops working.

3   Def. Out. Volt.      53.5 V                 42 V-58 V
                                                It refers to the output voltage of the rectifiers after
                                                working 30 minutes without the monitoring unit.

4   Def. Curr. Limit     63.5 A                 5 A–63.5 A 
                                                It refers to the current limit point of the rectifiers after 
												                        working 30 minutes without the monitoring unit.


Table 7-2 Descriptions of the Rectifier Control Menus

S.N      Menu         Function 
1     SMR Sleep       Used to put the rectifier into sleep. 
2     SMR Waken       Used to waken the rectifier in sleep. 
3     Fan Ctrl En     Used to enable the fan speed control function. 
                      With this function, the fan inside a rectifier can automatically 
					            adjust its speed based on the fan temperature. 
4     Fan Ctrl. Dis.  Used to disable the fan speed control function.

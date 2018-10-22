Void:[ setup();
turn lift motor on( set power to -.4 )();
]
Void:[ loop();
while lift position<= -7721 do();
output motor count to screen();
]
Void:[ setup();
lift power=0();
]
Void:[ loop();
turn servo power to .4();//IDK when to stop postition.
turn motor1 and motor2 power= .5 turn right 90();//no degrees sign.
]
//wait for incorder count
Void:[ setup stop drive motors power=0();
]
Void:[ loop();
move forword intill incoder count<=x();
]
Void:[ setup();
all motors power=0
]

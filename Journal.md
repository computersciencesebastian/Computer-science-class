
# August 18th, 2023
i am interested in learning about 
software design and infrastructure.
Learning how to make apps and improving apps would be something i would be interested in doing. It could be something im interested in doing especially if it's a app that could help someone.

# September 7th, 2023
**Why Should You Learn To Program**
- Programming is another skill that you could learn either to get a job or have a hobby or maybe its just something you think that would be useful to know.
- In my opinion, learning to program is a skill that i would want to learn how to do because it could show up as a oppurtunity for me later in life.
- For example, if your struggling financially and you cannot do anything else then maybe u can find a gig that could serve as extra money, or maybe you need to program something like a device to help your needs if your not feeling so well physically or maybe you just need a robot or something to remind you. Never the less, learning how to program is something 
that wouldnt hurt for you to learn.
```Python
from zumi.util.screen import Screen
from zumi.personality import Personality
from zumi.zumi import Zumi
from zumi.protocol import Note
import time

zumi = Zumi()
screen = Screen(False)
personality = Personality(zumi, screen)
zumi.forward(speed=40,duration=2.1)
zumi.turn_right(desired_angle=90, duration=1)
zumi.forward(speed=40,duration=1.7)
zumi.turn_right(desired_angle=90, duration=1)
zumi.forward(speed=40,duration=1.5)
zumi.left_u_turn(speed=28, step=4, delay=0.02)
zumi.forward(speed=40,duration=1.6)
```

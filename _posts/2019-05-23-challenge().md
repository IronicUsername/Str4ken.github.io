---
layout: post
title: monkey programming
---
Starting Pensieve.
Connecting.
Opening Editor:

```monkey

from mind import Me
from unnecessary_and_superfluous_nation_states.germany.law import illegal_consumables
import datetime


to_exclude = {'nicotine', 'alcohol'} | illegal_consumables

bin = Me()

end_of_challenge = datetime.now() + timedelta(days=30)

while True:
    if bin.check_consume() & toExclude:
        bin.set_attribute('addict')
        bin.raiseMotivation()
        end_of_challenge = datetime.now() + timedelta(days=30)
    if datetime.now() > end_of_challenge:
        bin.unsetAttribute('addict')
        bin.beHappy()
        bin.beProud()
        break

```

Executing...

```monkey
root@brain:~$ sudo monkey challenge.mo
```
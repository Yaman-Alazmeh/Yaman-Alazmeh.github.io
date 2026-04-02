---
title: "Generator Interactive System"
categories: [Game Dev, Unreal Engine]
featured: /assets/images/project_re1.png
last_modified_at: false
---
A third-person survival gameplay system built in Unreal Engine 4, inspired by mechanics from Dead by Daylight. This project focuses on recreating core interaction systems between the survivor and generator.
A third-person DeadByDaylight theme game built with Unreal Engine. 

**Key Features:**

-Repairing generators through interactive mechanics<br>
-Opening exit gates to complete objectives


The main gameplay loop revolves around repairing generators scattered across the map. Once a sufficient number of generators are completed, the player can unlock and open the exit gates to escape. Throughout this process, the player must remain alert and react to the constant threat of a pursuing killer.

A key mechanic in this system is the Skill Check mini-game, which is triggered while repairing a generator by pressing the left mouse button.

The skill check consists of a circular interface with a rotating indicator and a highlighted success zone. The player must stop the moving indicator at the correct moment within this zone to successfully pass the check.

✔ *Successful attempt*: Progress on the generator continues<br>
❌ *Failed attempt*: The generator’s progress decreases

Skill checks occur at regular intervals, requiring the player to consistently react and maintain focus. Successfully completing all required skill checks allows the player to fully repair the generator.

Once a generator is completed, it reduces the total number of remaining generators needed to unlock the exit gates, bringing the player closer to escaping the killer.

**Demonstration**

The following video demonstrates how the Skill Check system works in Dead by Daylight:

{% include video id="K24nphr32NA" provider="youtube" %}

### Screenshots
{% include figure image_path="/assets/images/DeadByDaylight/DeadByDaylight1.png" caption="Generator" %}
{% include figure image_path="/assets/images/DeadByDaylight/DeadByDaylight2.png" caption="Interacting with the Generator" %}
{% include figure image_path="/assets/images/DeadByDaylight/DeadByDaylight3.png" caption="Doing Skill Checks" %}




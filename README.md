# Island-Arcadia
An island floating in the VRChat universe. 

Initially created and uploaded to VRChat on Friday 21 June 2019. 
Published to the Public saturday 22 June 2019.

<b>Goals:</b> 
  - Jump Puzzle 1 (implemented)
    - Add mirror
    - animate completion rock button to form rocks into stairs
    - reset button for hoverbike
  - Jump Puzzle 2
    - Bed, pillows, Movie Player, Mirror
    - reset button for pillows
    - invisible chair for pillows
  - Jump Puzzle 3
    - Path to ride the Whale
    - Colliders and seats on the whale
    - Fix whale animation to be fluid all the way through/around
  - Other
    - Grass/ illuminated flowers
    - Spinning rocks
    - Shaders on rocks
    - Welcome Board
      - Discord link
      - Github info
      - Hinds
      - hideable
  - Optimize
    - Flag unmovable objects as lightmap static
    - decimate objects to lower poly count
    - combine as many objects as possible 
      - rock path combination
      - flower combination / grass
    - Bake Lights ( New object -> light ->light probes (for movable items bake the probe))
    - Reduce materials used
    - Combine textures and remap (like the rocks but for everyhthing else)
       - Use the skybox as texture for the pillows

6/23/2019
  - added toggle light
  - 

6/22/2019
  - addedd 2nd mirror for other PC's
  - added hidden jump puzzle
  - added hidden island
  - added hidden hovebike
  - removed all grass and switch to 5 small flowers for later implimination
  - made whale actually swim instead of just floating
  
6/21/2019
  - Made Particles toggle
  - Made mirror toggle
  - added addition music on toggle
  - Added plants

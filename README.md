# Island-Arcadia
An island floating in the VRChat universe.

Initially created and uploaded to VRChat on Friday 21 June 2019. 
Published to the Public saturday 22 June 2019.

<b>Backstory(INW):</b>
<i>The Name is unimportant. Names are like anchors, they ground you to your current reality.  Right now, Island Arcadia, is simply an island floating in the vast universe.  A well-preserved island of mysteries, wonders, and enlightenments.  The ambiance can change, all from the toggle of a rock.  </i>

For suggestions, recommendations, bug reports, and questions check out my discord: 

<b>Goals:</b> 

  - Jump Puzzle 1 (implemented)
    - Add mirror
    - animate completion rock button to form rocks into stairs
    - reset button for hoverbike
    
  - Jump Puzzle 2
    - Bed, pillows, Movie Player, Mirror
    - reset button for pillows
    - invisible chair for pillows
    - Add small cloud island
        - chess board
        - Meditation pillows 
        - reset button for chess 
    - shaders for cloud 
    
  - Jump Puzzle 3
    - Path to ride the Whale
    - Colliders and seats on the whale
    - Fix whale animation to be fluid all the way through/around

  - Secret Feature/room 1
    - teleport to/from
    - mirrors
    - lanterns
    - shaders
    - occlusion culling so it uploads initial area 



    
  - Other
    - Grass/ illuminated flowers
        - shaders 
    - Spinning rocks
    - Shaders on rocks
       - for when they appear have them materialize in
    - Rock pathing -> completion button to stairs
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
    - Quest optimization

<b> Update History: </b> (Japan time)

INW Update 
  - 

6/26/2019 
  - Managed children/game object folders for islands and paths
  - added path for 2nd secret island along with island
  - fixed some rock interactions
  - set several rocks to static for baked lighting
  - switch to unity 2017.4.28f1
  - SDK updated to 2019.06.21.13.53_Public
  - adjusted main island 2nd mirror distance
  - Scattered some flowers on primary island
  - changed description
  
6/23/2019
  - added toggle light
  - removed all grass and switch to 5 small flowers for later implimination

6/22/2019
  - addedd 2nd mirror for other PC's
  - added hidden jump puzzle
  - added hidden island
  - added hidden hovebike
  - made whale actually swim instead of just floating
  
6/21/2019
  - Made Particles toggle
  - Made mirror toggle
  - added addition music on toggle
  - Added plants

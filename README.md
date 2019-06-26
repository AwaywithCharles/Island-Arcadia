# Island-Arcadia
An island floating in the VRChat universe.

Initially created and uploaded to VRChat on Friday 21 June 2019. 
Published to the Public saturday 22 June 2019.

<b>Backstory:</b>
<i>The Name is unimportant. Names are like anchors, they ground you to your current reality.  Right now, Island Arcadia, is simply an island floating in the vast universe. The world can change, all from the toggle of a rock. </i>

For suggestions, recommendations, bug reports, and questions check out my discord: 


<b>Goals:</b> 

  - Make island spawns world not local

  - Jump Puzzle 1 (implemented)
    - Add mirror
      - Mirror Triggers
    - Hover Bike
      - reset button for hoverbike
    - Pillows
      - Pillow Spawn Trigger
      - Reset button
    - Floating Chair
      - 
    - Advance Features
      - animate completion rock button to form rocks into stairs
 
    
  - Jump Puzzle 2
    - Add small cloud island
        - chess board
        - Meditation pillows 
        - reset button for chess 
        - shaders for cloud 
    - Hidden Room
       - OnInteract
          - TelportIn
          - Disable all Local main effects
          - 
       - Objects
          - Bed (add late for filesize saving)
          - Pillows
              - Reset Button (SendRPC)
          - Movie Player
          - Mirror
          - Invisible Chair
       - Features

    
    
  - Jump Puzzle 3
    - Path to ride the Whale
    - Colliders and seats on the whale
    - Fix whale animation to be fluid all the way through/around


  - Hidden Room 1 
    - teleport In
        - Disable all features outside room
    - Teleport Out
        - Disable all features in room
        - onInteract enable initial world load settings
            - Particles on/music list on
    - mirrors
        - Walkthrough (for entrance) and nonwalk through
    - Room Effects
      - OnInteract
          - Play music
          - Materialize Spinning Rocks
            - Fixed Spinning Glow effects
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
      
      
  - Optimization
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

INW update

<B>Update History:</B>  

6/26/2019 - 72.67mb
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

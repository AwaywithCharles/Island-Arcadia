Goals:

  - Make island spawns world not local
  - Modify flowers in blender, rather than 6 pieces, make it one 3 piece cluster. 

- Jump Puzzle 1 (implemented)
  
   ~~- Add mirror
    - Mirror Triggers ~~
    - Hover Bike
      - reset button for hoverbike
    ~~- Pillows 
      - Pillow Spawn Trigger ~~
      - Reset button
    - Floating Chair
    - Advance Features
      - animate completion rock button to form rocks into stairs
      
      
  - Jump Puzzle 2

    - Add small cloud island
      - chess board
        - reset button for chess
        - Swap to checkers button
        - Shaders on cloude
      - Meditation pillows
    - Hidden Room
        - OnInteract
            - TelportIn
              - Disable all Local main effects
        - Objects
          - Bed (add late for filesize saving)
          - Pillows
            - Reset Button (SendRPC)
          - Movie Player
          - Mirror
          - Invisible Chair


    - Jump Puzzle 3
      
      - Whale
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
      - occlusion culling so it uploads initial area+
      
  - Other:

      - Grass/ illuminated flowers
      - shaders
      - Spinning rocks
      - Shaders on rocks for when they appear have them materialize in
      - Rock pathing -> completion button to stairs
      - Welcome Board
        - Discord link
        - Github info
        - hideable


- <b>Optimization</b>

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
  - Turn one mirror on, automatically turn off the other one.

# Planetary-Voxel-Sandbox
A 2D minecraft terraria clone but with gravitational planetary physics

  Structure of datafiles
    Array of Planet: Index { 
      X coord, Y coord, Array Layer: Index {
                                              Array of blocks: Index {  blockType (byte)  }
                                            }
    }

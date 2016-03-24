# SHA-256-HDL
Implements generic SHA-256 algorithm using VHDL.

## Main module
### sha256_core

                  _ _ _ _ _ _ _ _ _ _                      
                /                     \                         
               |                       |                     
      clock  > |                       |       
      reset  > |      sha256_core      | > digest
     enable  > |                       |
     message > |                       |
               |                       |                  
                \ _ _ _ _ _ _ _ _ _ _ /                      
                                                                     
                                                                      
      -- Inputs
        -- clock
        -- reset
        -- enable
        -- message ( 512 bits )
      -- Output
        -- digest  ( 256 bits )

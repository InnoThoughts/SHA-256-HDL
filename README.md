# SHA-256-HDL
A Hardware implementation of SHA-256 (SHA-2 family) cryptographic hash algorithm.

## SHA-256-HDL
### Top level module - sha256_core

                 _ _ _ _ _ _ _ _                                           
     (Inputs)   |               |  (Outputs)                   
      clock  -> |               |       
      reset  -> |               | -> digest
     enable  -> |               |
     message -> |               |
                |  sha256_core  |                  
                 _ _ _ _ _ _ _ _                      
                                                                     
    -- Parameters
      -- messageLength


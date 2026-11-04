          START
            |
            v
    Create seating matrix
            |
            v
   Check each seating position
            |
            v
      Is seat reserved?
        /       \
      Yes        No
       |          |
   Skip seat   Is seat empty?
                /     \
              Yes      No
               |        |
          Record empty  Check roll number
                        |
                        v
                  Is it duplicate?
                   /       \
                 Yes        No
                  |          |
             Record it   Check validity
                  |          |
                  v          v
             Display results
                  |
                  v
                 STOP

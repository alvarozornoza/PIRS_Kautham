                           PIRS_Kautham project
     
     The idea is to test 4 queries and 5 Planners.
     The queries are:
      
          - From an initial position the table 1 in a simple environment (No columns)
          - From table 1 to table 2 in a simple environment (No columns)
          - From an initial position the table 1 in a more complex environment (With columns)
          - From table 1 to table 2 in a more complex environment (With columns)
     
     The planners studied are:
     
          - PRM
          - PRM with bias
          - RRT
          - RRT connected
          - RRT star
      
     For this reason we modified the control file in order to create a mobile base robot. We also created 20 .xml files of the type:
     
               OMPL_planner i_query j.xml 
           
     TO DO: create 8 benchmarking files of the type:
              
               bench_query i_RRT.xml (for the three RRT planners)
               bench_query i_PRM.xml (for the two PRM planners)

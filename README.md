                           PIRS_Kautham project
     
     The idea is to test 4 queries and 5 Planners.
     The queries are:
      
          - 1) From an initial position the table 1 in a simple environment (No columns)
          - 2) From table 1 to table 2 in a simple environment (No columns)
          - 3) From an initial position the table 1 in a more complex environment (With columns)
          - 4) From table 1 to table 2 in a more complex environment (With columns)
     
     The planners studied are:
     
          - PRM
          - PRM with bias
          - RRT
          - RRT connected
          - RRT star
      
     For this reason we modified the control file in order to create a mobile base robot. We also created 20 .xml files of the type:
     
               OMPL_planner i_query j.xml 
           
     Finally we create the benchamark files to evaluate the algorithms.

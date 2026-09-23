TYPE: HDVRPSV
DEMAND_DIMENSION: 
DIMENSION: 
DEPOT_NUMBERS: 
EDGE_WEIGHT_TYPE: 
MCAPACITY:
Vehicle_ID    Cap_Product1    Cap_Product2    Cap_Product3 (# Note: All vehicles are homogeneous)
        1                        20                        20                        20

NODE_COORD_SECTION
Customer_ID          X_Coordinate            Y_Coordinate
         1                           5.4742                      13.6639

DEMAND_SECTION
Customer_ID    Dem_Product1     Dem_Product2      Dem_Product3
          1                             5                           2                             0

Depot_ID           Sup_Product1       Sup_Product2       Sup_Product3    
        11                            20                           0                             0
(#Note: Non-zero supply value means unlimited supply of corresponding product at this depot)

MDEPOT_SECTION

Depot_ID

EOF
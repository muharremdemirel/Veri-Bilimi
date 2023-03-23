## [16,21,11,8,12,22] -->  **Yanda verilen dizinin merge sort türüne göre aşamaları:**

#### - Burada amacımız önce parçalamak sonra bu parçaları sıralı bir şekilde toplamaktır.

                            [16,21,11,8,12,22]
                           /                  \
                          /                    \
                    [16,21,11]               [8,12,22]
                   /          \             /         \
                  /            \           /           \
              [16,21]         [11]       [8]        [12,22]
              /     \           |         |        /       \
             /       \          |         |       /         \
           [16]     [21]      [11]       [8]    [12]       [22]
             \        /         |         |       \         /
              \      /          |         |        \       /
              [16,21]         [11]       [8]        [12,22]
                    \          /           \         /
                     \        /             \       /
                    [11,16,21]              [8,12,21]
                            \               /
                             \             /
                           [8,11,12,16,21,22]


#### Big-O gösterimi = O(nlogn)
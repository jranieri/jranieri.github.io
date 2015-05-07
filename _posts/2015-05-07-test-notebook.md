---
layout:     post
title:      "Markdown"
date:       2015-05-06 23:34:00
category: article
---

    # Test of the file
    import math


*How does it looks like*

**Bold**


$$\phi(x,y)$$



    class points():
        
        def __init__(self, N):
            self.N=N
            self.points=Set([])
            
        def addPoints(self,x,y):
            self.points.add([x,y])
            
        def compute_distances(self):
            self.distances=Set([])
            for i in self.points:
                for j in self.points:
                    self.distances.add(abs(i[0]-i[1]))
                    
                    


    

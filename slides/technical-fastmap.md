##  Fast Loading Map Tiling

<img style="background:none; border:none; box-shadow:none; float: right; max-width: 60%; max-height: 60%;" src="resources/maptiles.png">  

### VERY Time Consuming! <!-- .element: class="fragment" data-fragment-index="1" -->
<BR/>
#### Parallel <!-- .element: class="fragment" data-fragment-index="2" -->
#### Optimization <!-- .element: class="fragment" data-fragment-index="3" -->
<BR/>
### 1 month for Perak <!-- .element: class="fragment" data-fragment-index="4" -->
note:
- besides wms, we also develop our own map tiling service
- map cutting is very time consuming, it may take years to cut whole malaysia
- parallel by dividing map cutting processing to 3 PCs & merge it together
- we avoid processing tiles without geographic features such as sea areas
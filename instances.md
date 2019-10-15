**Object:** Office Chair

*Attributes:*
legs: \['rolly leg 1', 'rolly leg 2', 'rolly leg 3', 'rolly leg 4', 'rolly leg 5'\]<br>
weight: 5
back: 'adjustable'
occupied: true
cushions: \['seat cushion', 'back cushion'\]

*Methods:*
lean: 'adjustable' to 'adjusted'
clean: \['seat cushion, 'back cushion'\] becomes \['clean seat cushion', 'clean back cushion'\]
legBreak: \['rolly leg 1', 'rolly leg 2', 'rolly leg 3', 'rolly leg 4', 'rolly leg 5'\] becomes \['rolly leg 1', 'rolly leg 2', 'rolly leg 3', 'rolly leg 5'\]
compress: \['seat cushion, 'back cushion'\] becomes \['squished seat cushion, 'back cushion'\]

**Object:** Kitchen Stool

*Attributes:*
legs: \['leg 1', 'leg 2', 'leg 3'\]
weight: 3
back: null
occupied: false
cushions: \['stool cushion'\]

*Methods:*
lean: not possible
clean: \['stool cushion'\] becomes \['clean stool cushion'\]
legBreak: \['leg 1', 'leg 2', 'leg 3'\] becomes \['leg 2', 'leg 3'\]
compress : \['stool cushion'\] becomes \['squished stool cushion'\]

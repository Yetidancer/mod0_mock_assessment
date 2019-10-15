**Object:** Office Chair

*Attributes:*<br>
legs: \['rolly leg 1', 'rolly leg 2', 'rolly leg 3', 'rolly leg 4', 'rolly leg 5'\]<br>
weight: 5<br>
back: 'adjustable'<br>
occupied: true<br>
cushions: \['seat cushion', 'back cushion'\]<br>

*Methods:*<br>
lean: 'adjustable' to 'adjusted'<br>
clean: \['seat cushion, 'back cushion'\] becomes \['clean seat cushion', 'clean back cushion'\]<br>
legBreak: \['rolly leg 1', 'rolly leg 2', 'rolly leg 3', 'rolly leg 4', 'rolly leg 5'\] becomes \['rolly leg 1', 'rolly leg 2', 'rolly leg 3', 'rolly leg 5'\]<br>
compress: \['seat cushion, 'back cushion'\] becomes \['squished seat cushion, 'back cushion'\]<br>

**Object:** Kitchen Stool

*Attributes:*<br>
legs: \['leg 1', 'leg 2', 'leg 3'\]<br>
weight: 3<br>
back: null<br>
occupied: false<br>
cushions: \['stool cushion'\]<br>

*Methods:*<br>
lean: not possible<br>
clean: \['stool cushion'\] becomes \['clean stool cushion'\]<br>
legBreak: \['leg 1', 'leg 2', 'leg 3'\] becomes \['leg 2', 'leg 3'\]<br>
compress : \['stool cushion'\] becomes \['squished stool cushion'\]<br>

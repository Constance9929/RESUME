# Python Office Assignment
Michael and Dwight will be out of the office making a huge paper sale to Robert California. Jim and Pam decide that during this time they are going to cover all of Dwight's things in aluminum foil.

In an attempt to enhance beet farming Dwight has converted all of his things into perfect boxes. Which will make calculating the required amount of foil for each item a little easier. In order to find the amount of foil needed the surface area for each item needs to be found and then aggregated. To find the surface area the following calculation can be used:

`2*l*w + 2*h*w + 2*l*h`

To give themselves a little extra foil to work with they also need to add the surface area of the smalles side.

*For example:*
A stapler with measurement 1x10x1 needs 42 feet of foil plus 1 slack
  `2*1*1 + 2*10*1 + 2*1*10 = 42 + 1*1 = 43`
  
An office chair with measurements 11x3x7 needs xx feet of foil plus x slack
  `2*11*3 + 2*11*7 + 2*3*7 = 262 + 3*7 = 283`

After wrapping everything in foil Jim decides that each package needs to be wrapped with duct tape and a bow to really tie the whole thing together. The amount of duct tape required to create the perfect wrap for a given cobe is the shortest distance around its sides ( the smallest periter of any side ). In order to make the bow an amount of duct tape equal to the cubic feet of the package will also be needed.

*For example:*
A Lackawanna County Volunteer Sheriff's Deputy Badge with dimensions 2x3x4 requires `2+2+3+3 = 10` feet of duct tape to wrap  plus `2*3*4 = 24` feet of tape for the bow, for a total of 34 feet.

A name board with dimensions 1x1x10 requires `1+1+1+1 = 4` feet of duct tape to wrap plus `1*1*10 = 10` feet of duct tape  for the bow, for a total of 14 feet.

Write a python program that reads from a file and then output the amount of foil and ribbon needed



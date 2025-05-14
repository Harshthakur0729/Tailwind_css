m-1 = 0.25rem = 4px
mx = horizontally margin apply
my = vertically margin apply
mt = margin top
mb = margin bottom
ml = margin left 
mr = margin right 
-------------------------------------------------- 
px = horizontally padding apply 
py = vertically padding apply 
pt = padding top
pb = padding bottom
pl = padding left 
pr = padding right 
--------------------------------------------------
Top and bottom margin or padding doesn’t work on a <span> because its default display is inline. When its display is changed (e.g., to inline-block or block), it works.
--------------------------------------------------
When you apply pixel values in padding and margin using Tailwind CSS, write it like this: p-[1px]
--------------------------------------------------
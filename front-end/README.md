1. Given the following HTML code:
   ```
   <div class="outer_div">
       <div class="inner_div">
           TAMID
       </div>
   </div>
   ```

   Write two CSS classes: `outer_div` and `inner_div`.

   `outer_div` should be a box
   with a width of 300 pixels and a height of 300 pixels. It should have a blue background with a solid black border of 1 pixel. Any item in `outer_div` should be perfectly centered (vertically and horizontally).

   `inner_div` should be a box with 50% of the width and height of `outer_div`. It should
   have a white dotted border of 3 pixels, and the text "TAMID" should be centered vertically and to the right of the box. The box should have a padding of 20 pixels.

2. Make this code work in Javascript:

   ```
     duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
   ```

3. Given two sorted arrays (*arr1*, *arr2*) and a number, *k*, create a method,
`sortArrays` that returns a sorted array of the first *k* elements. This must be completed in Javascript.

   > Bonus points if you can comment the space/time complexity of your method.
   > Bonus points if you do this in O(n).
   > Bonus points if you write this in one line and it runs in O(n*logn)

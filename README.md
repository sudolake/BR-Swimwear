# BR-Swimwear





to add a single item page (a page for an item)

1. go to an already created page (ex. item6.html)
2. copy everything
3. change what you have to, u dont have to change any css, just the image and the text
4. go to swimwear.html (where all the items are displayed)
5. change the "href=#" of the item to the item page you want it to link to ex. "href="../single-page-items/item5.html".
  THE END




to add a completely new item to the "all items" page:

1. copy this code under the last item thats in the code

<div class="item swimwear-yes bikini-no accessories-no">
    <a class="no-deco" href="#" target="_blank">
    <img src="../images/s3.png" alt="swimwear">
    <h5>...</h5>
    <price>$62.00</price>
    </a>
</div>

2. replace the image path with the image path you want to choose
3. change the title and the price
4. select what filter it is (ex. if its a swimwear, the classes should be: item(necessary) swimwear-yes bikini-no accessories-no)


note: you have some items that have prices but dont have an image to them (Almofada v.1 & Almofada v.2), for these, change the image and the classes (so they get filtered) and remove the class "blank-space" from the "img" element

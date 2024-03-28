<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
  <title>Responsive Entry Form</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1 class="form-title">Data Entry For ebay/amazon</h1>
    <form id="entryForm">
      <div class="main-user-info">
       
        <div class="user-input-box">
          <label for="productName">Product Name</label>
          <input type="text" id="productName" name="productName" placeholder="Enter Product Name" required/>
          <span class="error" id="productNameError"></span>
        </div>
       
        <div class="user-input-box">
          <label for="productPrice">Product Price</label>
          <input type="number" id="productPrice" name="productPrice" placeholder="Enter Product Price" required/>
          <span class="error" id="productPriceError"></span>
        </div>
       
        <div class="user-input-box">
          <label for="amazonSeller">Seller Information</label>
          <input type="text" id="amazonSeller" name="amazonSeller" placeholder="Enter Seller Info" required/>
        </div>
       
        <div class="user-input-box">
          <label for="amazonReviews">Number of Reviews</label>
          <input type="number" id="amazonReviews" name="amazonReviews" placeholder="Enter Number of Reviews" required/>
        </div>
        
        <div class="user-input-box">
          <label for="productCategory">Product Category</label>
          <input type="text" id="productCategory" name="productCategory" placeholder="Enter Product Category" required/>
        </div>
       
        <div class="user-input-box">
          <label for="productBrand">Product Brand</label>
          <input type="text" id="productBrand" name="productBrand" placeholder="Enter Product Brand" required/>
        </div>
        
        <div class="user-input-box">
          <label for="sellerName">Seller Name</label>
          <input type="text" id="sellerName" name="sellerName" placeholder="Enter Seller Name" required/>
        </div>
       
        <div class="user-input-box">
          <label for="sellerRating">Seller Rating</label>
          <input type="text" id="sellerRating" name="sellerRating" placeholder="Enter Seller Rating" required/>
        </div>
       
        <div class="user-input-boxs">
          <label for="productDescription">Product Description</label>
          <textarea id="productDescription" name="productDescription" required></textarea>
        </div>
      </div>
    
      <div class="form-submit-btn">
        <input type="submit" value="Submit">
      </div>
    </form>
  </div>
<script>
    document.getElementById("entryForm").addEventListener("submit", function(event) {
      event.preventDefault(); 
      var formData = {
        productName: document.getElementById("productName").value,
        productPrice: document.getElementById("productPrice").value,
        amazonSeller: document.getElementById("amazonSeller").value,
        amazonReviews: document.getElementById("amazonReviews").value,
        productCategory: document.getElementById("productCategory").value,
        productBrand: document.getElementById("productBrand").value,
        sellerName: document.getElementById("sellerName").value,
        sellerRating: document.getElementById("sellerRating").value,
        productDescription: document.getElementById("productDescription").value
      };

    
      console.log("Product Name: " + formData.productName);
      console.log("Product Price: " + formData.productPrice);
      console.log("Amazon Seller: " + formData.amazonSeller);
      console.log("Amazon Reviews: " + formData.amazonReviews);
      console.log("Product Category: " + formData.productCategory);
      console.log("Product Brand: " + formData.productBrand);
      console.log("Seller Name: " + formData.sellerName);
      console.log("Seller Rating: " + formData.sellerRating);
      console.log("Product Description: " + formData.productDescription);
      
        document.getElementById("entryForm").reset();
    
    });
  </script>
</body>
</html>

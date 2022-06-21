# howtointegratemobilehtml
integrate Naweri wallet Into Your HTML project and start receiving payments from mobile money in africa
This Integration Is Powered By The Naweri Wallet And Designed By Naweri Industries

Just Copy And Paste The Code Below In Your HTML Page To Start Receiving Payments Online.
Remember To Read The Documentations At https://wallet.naweri.com 
And Create A Business Account To Receive Payments Via API Key. Personal Accounts Don't Receive Payments Via API Key.
The Country You Choose Is Your Default Currency


<form action="https://wallet.naweri.com/api_request/" method="post" enctype="multipart/form-data"><br>
<input type="text" class="form-control" placeholder="merchant email" name="merchant" value="merchant@domain.com"><br><!--Your Merchant Email Here-->

<input type="text" name="useremail" value="customer@example.com"><br>
<input type="text" name="username" value="Naweri Clinton"><br>
<input type="text" name="userphone" value="+256751021147"><br>
<input type="text" class="form-control" placeholder="itemname" name="itemname" value="Item Name"><br>
<input type="text" class="form-control" placeholder="itemid" name="itemid" value="Item ID e.g 1" ><br>
<input type="text" class="form-control" placeholder="price" name="amount" value="3500">
<!--Don't Change Here--><br>
<input type="text" class="form-control" name="itemdescription" value="Short Item description"><br>
<input type="text" name="currency" value="UGX"> <!--First Check Our List Of Currencies In The wallet.naweri.com--><br>
<input type="text" name="initdeposit"> <!--Do Not Change Here--><br>
<input type="text" class="form-control" name="successurl" value="https://yourdomain.com/success.html"><br>
<input type="text" class="form-control" name="failedurl" value="https://yourdomain.com/failed.html"><br>
<button class="btn btn-outline-warning" name="pictonapay" type="submit">
<i class="fa fa-cart-plus">
</i> Pay
</button><br>
</form><br><br>



Build By Naweri Yoweri Clinton || Naweri Industries

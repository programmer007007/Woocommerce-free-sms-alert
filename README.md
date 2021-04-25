# Woocommerce-free-sms-alert
Today i am going to show you how you can send sms for free using your android phone when someone makes a order on your wordpress woocommerce site

First signup for free otp api on <a href="http://freeotp.ricomart.com/">http://freeotp.ricomart.com/</a>

Below is the panel that you would see . Now you need to go to API setting

<img src="https://res.cloudinary.com/didyouknowthat/image/upload/v1619321435/rq1_ir7wup.jpg" />

As you can see below the lines with black are the important setting , just note it down .

AUTH KEY - Shown below

DEVICE - Z2 Plus

Sim - It should be either 1 or 2 , 1 means send via first sim and so on.

That is it. Let move on to linking this api to your wordpress  site

<img src="https://res.cloudinary.com/didyouknowthat/image/upload/v1619322131/rb4_asmp6e.jpg" />

&nbsp;

After the above steps are followed you need to install this given plugin : <strong><a href="http://google.com">Download </a></strong>This plugin is based on an sms alert plugin , it's modified to fit this free sms service.

Now once you activated a plugin it would look something like below . By the way this can be found under woocomerce -&gt; sms alert

Fill in the details that you have noted above in to the respective boxes and click on Save Auth Details. Then you can enter a phone number to test if the api is working as expected. Don't enter the same phone number through which you will be sending sms.

<img src="https://res.cloudinary.com/didyouknowthat/image/upload/v1619272190/r1_adu3iv.jpg" />

Here you can modify the template and the timing when you would like the sms to trigger. Eg : Like below when you have the given box ticked like shown below , the sms will be triggered to the user when he places a order. Similarly there are other trigger setting which are preety obvious by its name of what it does.

<img src="https://res.cloudinary.com/didyouknowthat/image/upload/v1619272191/r2_hhaobu.jpg" />

Now let understand how to configure the android app, You can download the apk here : <a href="https://freeotp.ricomart.com/assets/mobile-sms-gateway.apk">Apk Download</a>

After you install and open the app the below page will be shown in your phone. Just enter the server name https://freeotp.ricomart.com

<img src="https://res.cloudinary.com/didyouknowthat/image/upload/v1619325279/WhatsApp_Image_2021-04-25_at_10.02.26_AM_v5ss6l.jpg" />

Then you need to login in to the app using the same username and password that you had received in your email

<img src="https://res.cloudinary.com/didyouknowthat/image/upload/v1619325280/WhatsApp_Image_2021-04-25_at_10.03.09_AM_brfhgo.jpg" />

&nbsp;

How this work is pretty simple.

Your wordpress site connects to freeotp.ricomart.com site using the auth details and then it pushed the message to the android app which is logged into the account.
Note you need to keep the app always in the background so it's always connected to the freeotp.ricomart.com server.

This way you could use the existing sms plan which anyway goes to waste in to ur business use.

If you doing huge say like getting hundreds of order better get a 3rd party sms api.

To read such kind of interesting article visit <a href="https://blog.ricomart.com/free-woocommerce-order-sms-wordpress/">Free Technical Articles</a>

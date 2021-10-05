# Its Paid
   ## Overview
 
   Category: Forensics
   
   ## Description
   I heard that admin leaked something somewhere o.O.
   
   ## Approch
   
  Let's click `Get Started` and try to buy any course
  
   ![22](https://user-images.githubusercontent.com/60851229/136033943-4e1f6ada-a4ca-433e-b953-18b4365ce67b.png)
![333](https://user-images.githubusercontent.com/60851229/136033948-e1bcc93d-83b8-4b16-8542-de62f8cd5429.png)
![44444444](https://user-images.githubusercontent.com/60851229/136033949-b66f1a8b-59d6-47e6-ba3c-4cc68b18a665.png)

 

Not able to buy anything so let's intercept the request with burp suite.

![iits](https://user-images.githubusercontent.com/60851229/136034005-744d4c02-8450-4b6a-a8ec-0f6df9260bba.png)


Change `amount = 0`.
Now let's buy all the 8 courses.

![555](https://user-images.githubusercontent.com/60851229/136034031-b1cfcf13-1202-4e6f-af27-a42ba785e8e9.png)


While checking the `ZERO TO HERO` course, the admin credential is leaked in the url of the browser in the video. Using that I logged into the admin area.
![7777](https://user-images.githubusercontent.com/60851229/136034060-97fac18a-fd06-4332-9912-0a8e8aa2cfb1.png)

![8888](https://user-images.githubusercontent.com/60851229/136034070-248509c9-75a5-4919-8299-0941fdaecff9.png)
let's check the cookies. Here the `special_person` cookie is set to false, try changing  it to true.

And here is the flag!!


![999999](https://user-images.githubusercontent.com/60851229/136034107-00863962-2e08-470f-93ed-8c73f9ec22b5.png)



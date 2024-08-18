# Baby XSS

## Attachment
[ctf.gemastik.id:9020](http://ctf.gemastik.id:9020)

## Solver
Open the challenge link.

![Capture_1.JPG](images/Capture_1.PNG)

Just do “View page source”

![Capture_2.JPG](images/Capture_2.PNG)

There is a suspicious javascript code

![Capture_3.JPG](images/Capture_3.PNG)

This code will execute code on query parameter x. This is one example.

![Capture_4.JPG](images/Capture_4.PNG)

Immediately we create a payload to take the cookie and send it to a webhook.

![Capture_5.JPG](images/Capture_5.PNG)

Then you will get results like this.

![Capture_6.JPG](images/Capture_6.PNG)

Finally, to get the flag you can do this by sending the url and payload via the bot admin. Don't forget to change the host from "ctf.gemastik:9020" to "proxy".

![Capture_7.JPG](images/Capture_7.PNG)
![Capture_8.JPG](images/Capture_8.PNG)

## Flag
gemastik{s3lamat_anda_m3ndap4tkan_XSS}

# XSS-Attack-Detection

I have found the date and time that XSS attack started.
![Screenshot 2024-10-02 at 2 37 04 AM](https://github.com/user-attachments/assets/52d2ec18-d23e-4647-bd80-201b809edbbb)

I have also now found the IP address the attacker is using.
<img width="1119" alt="Screenshot 2024-10-05 at 11 09 25 AM" src="https://github.com/user-attachments/assets/70bab410-b0cc-4201-9e59-5bc5999b3ad0">


I can see that this is an attack because it has a script tag. The %3C and %3E are URL-encoded representations of < and >, which are used to inject HTML or JavaScript into web applications. Attackers encode these characters to bypass filters or restrictions in some cases. These elements together strongly suggest that this is a reflected XSS attack attempt.
<img width="1115" alt="Screenshot 2024-10-05 at 11 17 53 AM" src="https://github.com/user-attachments/assets/23ef2b4d-6e7c-4fc6-8fee-2dca0d2f5d91">

We know that the attack was succesfull becuase the "200" status in the log indicates that the page loaded normally, without error, and executed the request as expected.

# chronocrypt

ChronoCrypt: Temporal Shift Cipher is a web-based encryption tool inspired by the Caesar cipher but enhanced with a time-based shift. It allows users to encode and decode messages using a specific time in the HH:MM (24-hour) format as the cipher key. This time-based shifting tool makes each encryption is unique depending on the time input, offering an effective way to personalize and secure message.

The message is divided into two parts by a space:
•	The first part is encrypted using the hour value.
•	The second part is encrypted using the minute value.

STEPS TO USE THE SYSTEM
1.	Input the time in HH:MM format
2.	Enter the message to encrypt or decrypt, ensuring there is a space dividing the two parts.
3.	Encrypt: The first part of the message is shifted forward by the hour value, and the second part by the minute value.
4.	Decrypt: The ciphertext is shifted backward by the same hour and minute values to retrieve the original message.

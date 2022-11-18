---
layout: home
---
![Logo](/banner.jpg)
# Documentation
Why sendlab?
- Send passwords, memos, secrets, tokens, and high-privacy items with total security knowing they will be deleted once opened by the receipient.
- As the first open source project to do this, you can finally trust that it is secure and verify that the messages are deleted after receipt.

## Getting Started

1) Install Python, pip and then Django
2) Clone repository at https://github.com/runar-org/messenger.git
3) Open project and setup database with ``python manage.py migrate``
4) Serve the app with ``python manage.py runserver``

## Technologies Used
* Skeleton for javascript free responsive web design. http://getskeleton.com/
* Python, full stack using Django.
* AES for encryption, using the python toolkit pycrypto: https://pypi.org/project/pycrypto/

## Key Features
Determine most important features to an anonymous messaging system.

* complete anonymity for sender and receiver 
* permanently delete messages after receiving or timeout
* set your own decryption phrase or use the system provided encryption
* use 0 javascript to allow TOR browser in high-security mode


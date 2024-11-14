---
title: Friend Stream Notifications
layout: default
nav_order: 19
---

![Picture](assets/media/friend_stream_notifications_title_1.png)

Twitch
{: .label .label-purple }

StreamerBot
{: .label .label-blue }


# Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


## Description
Get a custom trigger whenever a streamer you follow goes live.

![Picture](assets/media/friend_stream_notifications_title_2.png)

---

## Import Code
```scss
U0JBRR+LCAAAAAAABADNPFmTokq67zfi/oeKvo8zVgOKVZy30ioRy7JLVEBun5hgE9BkGQEVJ85/ny8TRFFcqrs6TncE0S25fPuaZP/nf//n7u6LZ8Xalz/u/oN/wE9f8yz4+aWzdC3fvBvFS0vz7gZB7M5cQ4vdwI++/DOfqyWxEyzx7Fhbe5pVDKysZQQz8Qh9T90zxYBpRcbSDeN8UPCjeJkYZNc/7pw4DqM/vn7NNru33dhJ9Hs3+DojuPwrIrj8yz/E5d6JPXSIUCAm/pORA/AThHZjnuu7XuJJBWp4EI/9RWZ8MbUSH7QMK3jz/9mbu90QGXZNjD9rNBlOmxk1rmEatYbBUrVHyrJqdaNpWXSTe7R0bYccWfbvxEqsMmLkveVrOrLwnsAPqzSyMVBiWp1l4HXdKA6WKUyaaSgqzfqA1Mh8exkk4UcWaGitpRHwtgr6UvPNwCu4fjJuBL6RLJeWH1eNxkvXtkEqh6w+YvcByxm2aZm0+VBrzBpUrcE+UDWNMtjao2noD9pjHX40DjHPQKQhZg/9UD8eOcv4PfOjnR78eTj61/7HnyVGnepNFTEfFBhZc2Q8J+NLa2YBkw3rBDoZbv/x/bvsgqTW0ffvb66xDKJgFt8PXsbfv3eWgM86WC6aje/fVw2w2TpVp7nv373ICJbI1e9NhI4B/uieozSKLe++HSytX7Dt5+84sOJftGsXPN6Zre8PN2wZ6P4pSn1D8GNrOdNAxOeX5fuPHVAp0/Xt+7EWLaL7l01s+USXzy8dWOsYJmCQvSjwb0GtHZjWk6+hNHKv49QOELIyA7kXPC+JsfH9At7K1q9QWPB+setZ9yNr6WrI3RIzvS4HaxPfv/hGgGURFaiVV/x5bMt6GluYtdjQTWUQ6p5hT+poa/JS/G1NvR6/6y8GK53foGldDHWG3fYXJtI9KdXkt4fnYUgbDErUtDW2lAGlylQy5lFijKNB25e2msz6wguLzLq40v3BSvWHyQj+1udXxl32DcY21fjA/DYrmF1xfW28v3DQVBaR4VfjKvFOqsqdBcajj0THYOJt5Z5IDAxPclSgTd0C7jb1anQlV+fRXOAH0VQZbIWXwXD0ghIdzxlSrxbsI7SfbKHboqfeJpymra3Z7ZF9daQCTgCDadjvoyf3bdRY9+eC+22/JtUU1TH5iW3URfgb4HR7mJaV7m1Y4cWhzG7rGWAh3R/aU2YTqjJLCc+UDbKpH40P2i7s2W4BDwKb7I+fDshTllamMgQcWhNNptGk3nKA97zhcfGEkeYg74WR2tu39mK3B3czjjznap40N9utmaqAHOoSpckc6Ac319InTuBBTmlrNfVCGBvar+1FgZ8BfDK9DqWOgGd8B9a92VOPW+mwl6YMRqbMJkR3gF7V60QGMynWwntKVXrJVF7v8XoZOLo3QKDH+PdKR+JKY6RkwnC0Ae+FDjc3u2+YD4mqGPaQ6SRTRop0ApsDPeGWwN+xXpfSKTMJXrF+Z/xYm3IvOsCvY/FAsyKi1z3PynznN6spE9mvHQ7lc7FdvenMYPk6zHnbrliXvQtV9ylQGLSd+FKie1ifd3AOnm50+i5b/zx5sbEM/JHMenpqLwQUg7xBT7wh6LuI7SEGm1wBnzxNHmT88t9s02Uf9nrLcsqo1dIzebMgd1r3WKzbidAZLDWltSY25TYSwV1U0JE9YFOUCbISeNXRuwNU6NbBMwOeVPDhRA/Atmh1XKb7ZG1XTK3rPP5MHo1Bf1MT+4S0kfRdIayiEfQ0JXR0M73E9AzplgB+p64p4lx74VqgJ0Gmh40qnAvfsvMFI5nYNaFF6pqhyQ+C4X6sag9mqgj21O+tQKbzKfaR8Pt4D5GRqGF5zoE9HDydR7y2o/NSV5NNX+cngZnhH2GfqclSYr6gRb/dcsHfgG8dOMAHZLisZDBSCjge8arFle0I830QCG0HbG6AjK5I/Kmq2GFZ5hW4YV/dxjZn9nRPXb22h65MqSnGSW2DzIheU/bY48D+1XDKZH7ASFtM348TCeIfxBKQOW0KL1Ljm9t6ALjJWJa2BtPxVYVyK3lys+1nj1WhKxlvudCgC5vDfPam8mZ7rP8Z/dQVm+ghsyulutuiDF/a2yBeZ5/EMEZn0EKAOKcpw6DA+YjHme72kMqQ+JkO6xL8zcUS6KjKmCBj2xX9HtbFBfgLCsdWfdT6pkOOoXoI9CrLNQR3bQuLW+QiRCSe0LEJuNy6xp6N9r7pkC9FbO+qKw3sSOTR1uC5rTra61ZZNq0Z5Efb95R9nsrsXJXXJzZBeLLYrFQKfIH3GPTaPf0mHnSnicWwMsS0LcZ7JlEFPlU+tkxHEUfBtlAC8puAzS5BZyN1YmJZROrIKXxHYZ9djA/JleZZDiH21Pb6wE9JW8AH3p2Jcbf52brGI4D/FAgSib95nG0kI2WQ83ET5XwYqUqHVkneNgwr9jobY6aK6YCu2iNGQgb/eM4H0dU+5+kCTbfE2zIOEt/Zain7AnQ51sim356f1v1cd/p5TlLpN6r83+H+oNNTxga/QnLYHe+QCr4J8pg1iU9uRZ5whXef7isJfpGt8hLIdYHxJnkWyPRinpD5zh6Ou8vz8qFu8n0HdGMbm2vtp0BUnLmqtAjeAi81bsjDPjNHKMUvTW7YIshOZJCvMht0S2w5ogvgsQ7kuuzVOPh3xSP7dJ/P9I/A/5XRbZF8FPzjeX6VY1xRz4CPZHXvLbPX7eYF5Ed0Y6r02PfCN66xH54TuXqd1Bpvdn40Kmqf58Y/3t3WAPvMMS+h171fpXQmRrp74FPL/mjvkxXQjQVanIu1MO+6nPdwod5Z45pzIXikRtx+cx9XU6UV9v0812yzlOlyAfiP0Gpz28y+6W2fUXEfYGUy0uK9Tvz/DGIjZ9XzWNCl3Crb3OWj/YWIoFaj9a5Y+PIRj2tq8A8QNyFPdCAvqPS/N+5BcmS93gstL/NB+3q4Q5u8g+NY4Z926ySoH015EggLoFPpQW4CuUT3gi/eyamN/Tjoi7yhJp60McE+zZei35AMZXHx2u7tavAYYosLcj2Ip1X+rkX6FrAfju8JxKQB0LidyibCeZpRb+E+CcJ07WLKnjcmMl86Wwt8/yvO5yBeKwzIPWUnma5VwiP1pFHAm+DYOzblwRzDneD6GWL9kOEW6uhDdWahvxru56Bq3A/hAowEckXM1xHuyQwxHmQPs5XlLtW6kcWo8H3XR1ChZp+OnriDd8kEajCAERzjciHWvg6VXopjlJH7cgP3LNrO7n1I4EiRm8Hrmefjkgp63drZEfEle70Efcz6ao7hLx53vgD05KzP0Znev1UYe583quuuPAaAHQA8Uh+Rum5HhwC1aOYPwJ8qb/b79jHHJWwZfg/nJWGV778s7+zZ54f5/hOoFYDWHWw5BX/e7pnvWCfpHU0X5JrRQvCHOto3KJCj12GP9qTAPrYCwnr1Zo8W2Zwrex7kvLAvlm1XdNT6IOfBk4N7QWDbkfD8WNDVX4RQDzQCUpfAc4hTH+H+Eu53OYAPxMBxg4zjvG6Sr39tL8LX0VNTaAuVvvIIv0Jf5Pqen8qo6J1d15GKOHs5r/mROfnjkzjwDXBGwJuLelJBp56vn+mQUwGPXWX8iOuB3AcYAfDt63v65AoXacrj++gG+Fd0+eBxSQyGuHArLw50k9QVCti3Lk9+P5ogr/gZWUH8/61oUplOrE4yXvefrsPP9s9tC/tyvF4Ce8I6jKivR7ZLfKXgCjfgTN2gKx+xLTE0+c0P2lW+9reiZ0CBz4JaXmyZ7R+yq23WV5UWCuRzvxVt3saBnIUmOduPyOtw/e9Ely8Gpky7UOuEegfnl7fL7fXAxiAPp3UZn8+gSKnjfU7zAYi5X3GMfB3hvk8rgjwGQS79YDJoAes5En/nL+zb/OlkjsZLoco41GwEeXxb2Lw922vhbO/jV+oB2o7lDj7f+EE9QFuFoXH+naqjnEfUrq7cuDrDRe9uzqv8/OQG/Llb/OLZOv/kyXOv2+kj82/B8+KcLnVWDtXnRdlTnDcV+SnOvyvPQirgt1A1j8/rxGf2NIZSq1eqAUHmGu7xPQe2Vd+/hzwUfKtIG9RgBfUtd9v52+V88pY+x2t1PVvm41E/ruhblvqULWS1y/ZapY+aPLVf251S77S/QNvjs9uiNodYcbau+bvOg/ZnL+Tc+Syfz9eJu/Pzf7yf9E72vL/tTCBG4EdXf1+PitTJwAdzvOs5HfYKxjLgRIG+j5wCr4OzzujgTOLi+aiBeY529e/g1WC4/Xkr6aGYEdRPjt4BfOaFDEC/e17W3xVnuzwE8vqj/u5gpmIZtvF5VOaTd/mwVa/uj4EsUtx7VBW1RDf5DgZ/e+PjXvEwEXlCXzjFfTlP2vU2Hn9KZ+aNoIofGc6/QidLtkt66Pg8WWQ2sKYTSQDjne+tdGZ9M781ZQA2i8AeN+FUCZFa4v3f9m1EjlMn0pSQ6J3qceCTuLoqD22dRwzuXeY9mMvfSBS2h89cRSz/Qk+yb6VIr2sLcJ/hgX17FO5FAN4OwGmqk913OE7Jti70jggfJkdy+bj+n8N3vftm50I/j/jjsaqIXeCZC3vIU0UIBC/3yZ2iLz3Tj30yzYUGlcEG+h2wlQXp1eDvQ0Y3wN755PntZxcgW8wPcpaU2XMR20P9yKd96FwFeCu0badso295rxTycH/QV5VFsJNHfxEja7SoOB+9Aufz9f8b9h0ZXhLC6/C3JBPYe7wNqmPhJX7yMWO0CS9zuVNJ3rc/S+tlW6/UtZYBdZdOevtAux8vTf8pGTESS2oJggMrgy6CHl05qzzHT8DFYsg+IDfE4TxBq6vrPsL+SkIA51ovFMf0G3uweTx8UVOdoYsc5n10zENp18/p/WhvViP0YT9EeDmBOg3yOqcLPO1YXRH7DKR2Mhg4vxr6CGA5+Zm7mH1vmOvXNd0gsYMn+bQtjClb9yHXa1+u726pZ7JvVgb4DCVV61KM8wrweeBLaJxHp5BTr8jZUAYbn5MMdEYEP9uh9Po1uR3AKNUDArZxqBO5BfAG7IlLiU4QfrK9Emz/TA55mz67GjnX6W2ndcghcp9YwKEH9NQfzEHmrnrpG4gbaJnUJddgBqCDvaw2YQp+leBf1/VrctmdR2I9LcmF15lNpNdNHHd/ihYxj9nYnspyOYBd/zm5gG9fQe0XqRMU456PpPSiA9kMwTY8XOeNZNpRGUkyvPWP0wR5ps6oEBelni5DXSJBnDuQ0aQCl5+U01zjO4nuSRHOX7Hs8+8c8FloiH0BPtMl+pJ/f/EBXpbqNfw9xxlYTaEbV8L6aR2koYbyRYjvwgE9YAOkN8ki49o3LRfiBNjrEPdI8bf2Jd0rYPYu1vbH++N8bqj0fFOm8Xl0gPtLQ1n1srxZRCV/QHU8rAeQv1I/E+uAhpbqqSQPM/nJgRzKsG+Me+fh8xLO6T4nBnxSv0YiZ0aZTmBfIvAsrfPrq77iUv/qQPcn4Kt98AcpOZufSEyuk7fka1hXybeeH/vW7EzucfhtCY+/t5cWO9gGhesSfMehRepKkreCPpvED57UsgE+hy7WppV1/OfUJl1pjc/tVVm8sTb5fb89Puib4fy4D/n2Wt9iny41+gsaGfUBjhunvqLoxWHaQu7k0l+4tIzAC11knbnDaFpIS0extqy6fElmRNrKEq0oQfE4kLSliy9lXZpbmnV6DTG7p9lsNhmNbdK1Bls3ag1Ne6hxM/ax1mga1qw+s/QHSz9ZurZc28F4UvfUmTucHP5zPFZcZyVXpj52x9P1TWuDL4eWbnf+89LlzZWGyC3eL6v70vXmYoIRoOxe9BnmUOYj90DVzZrWZIAlOsfWdKiIa02r8ahzjGU1tOaPMIemqLO8Obpy/AHOUD/AGTO484P4Lg4Sw7lLfGRF0V0aJHcLP1jfrR0tJr/M4Dzr/q/ToeDPGQ7qumWZ7MyqMfRDvdZ4NM0aVzfMGkVpM+uBZvS69fDZHPwZ7Srz8OLdYR6Du/E2dNN8MCjdZGozg6FqjUaTq3HNWbNGaQ8mqz00Hi3zlIOX2LC7l1xJanbP+5xrqDakM6SCmJEWRpZZTe1thB3svftnDm8HK7twn93e3r0Cd+kBIeWXa0uPAmNhxSNrucovo58OtpFr+XF5EF8JXe7vh+f/m8D+f0CgMx5/sTZhsIwtE9/kJz7gnrnPb6qf/t8E2WhNt2Ltvgl0/vVffGkuj6xBAAA=
```

---


## Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Restart Streamer.bot (or rightclick the trigger and hit "Test Trigger". *The action will automatically start once your Twitch account connects to Streamer.bot, so you will only have to do this on the initial import*.

3. Done! 🥳

---

## Variables

After setting the action up, you'll have a custom trigger called "Friend Stream Notifications" that will fire once one of your followed streamers goes live. You will have a bunch of variables available for use:

![Picture](assets/media/friend_stream_notifications_trigger.png)

![Picture](assets/media/friend_stream_notifications_variables.png)

- `%user%`
 
   The user's display name.

- `%userName%`
 
   The user's login name.

- `%userId%`
 
   The user's ID.

- `%profileImageUrl%`
 
   The user's profile image URL.

- `%title%`
 
   The stream's title.

- `%channelDescription%`
 
   The user's channel description.

- `%gameName%`
 
   The stream's category.

- `%startedAt%`
 
   Date and time of the stream start.

- `%language%`
 
   Language code of the stream, e.g. `en`.

- `%thumbnailUrl%`
 
   URL of the thumbnail in 1920x1080. Note: might not be populated right after stream start.

- `%isMature%`
 
   Bool whether the stream is set to "mature".

- `%tags%`
 
   The stream tags.

- `%isModerator%`
 
   Bool whether the user is a moderator in your channel.

- `%isFollowing%`
 
   Bool whether the user is following your channel.

- `%isSubscribed%`
 
   Bool whether the user is subscribed to your channel.

- `%isAffiliate%`
 
   Bool whether the user is an affiliate.

- `%isPartner%`
 
   Bool whether the user is a partner.


---

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| November 14, 2024           | Code optimization | 1.1.2 |
| October 26, 2024           | Added more variables | 1.0.1 |
| October 25, 2024           | Release | 1.0.0 |

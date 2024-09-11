---
title: User Inventory
layout: default
nav_order: 3
---

![User Inventory](assets/media/user_inventory_title.png)

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

Users in chat are able to store items in their own inventory. They can either loot a random item or have an item added manually. Upon usage, specific items can trigger specific actions and allow for funny interactions!

![User Inventory](assets/media/user_inventory_title_2.png)

_Examples:_
- a *VIP voucher* that grants a user VIP
-  a *Potion Of Silence* that mutes the streamer's mic
- a *Ban Hammer* that allows the user to timeout another user

- - - -

## Import Code
```scss
U0JBRR+LCAAAAAAABADtfXlzIkmy5/9rtt+B6bUxe2s9WZ330fbemglKXJKoEkgJoqttLa6EFMnxOITQ7Hz39Yg8gDwAqaQaVXW1mbokkozDw93D4+dH/PN//o9S6ZcxW6Jffi/9k/8Bf07QmMGfv9wu2LzUWLJxqTF5YJPldL755R/Rd9BqOZzO+beWaD1GLHnwwOYLfzrhT9QP8gc5eUDZgsz92TJ62JgslvMV4X8ufi8Nl8vZ4vfffgsb+zDwl8MV/uBPf1vBGP6vH3f/YbgcB7tjmLZXkzMStTlZBUH8bOxP/PFq7Caj4Q/5s3+Jb/xC0d6UUTgQ+OSP8JNS/Eg89ikfsm3YloqQKlmUKZKuEVNCpkUlE+u2xxjyLNuJByde++8VWwlKGqps6zpWJEwMQ9JlhUlIgzY0w/OY7BBHY2zvTTZBOGC8VyAS23vySIIVZdX5dFz3F2JNfi95KFjsfStewj9y1vDPklKSSmeUis/3uh3Mp6vZkaUP6RWs0WYBxM/rfI4mdDpOliXznEwnZDWfQ7N5T5dzfzCAZdtdi9R6RK2Mx9BRQywN0wwTqTqSbJMAgTWbSAhbtqRhZKmG5jmmTnYnsLOqTNMJLCyVFOqYku4xR8KGgyRqWx5SNGTbzMi8utzMOH1hJdNPClduu3qLmNX+3H36r38cmu2crdE8mqziaJahGVSyVVuWdMeBESPLlDA1ZKSqtont7IjDySomUrCjOJJiUkvSka5KWLewhBVMKZZlRHS7aLKKor7eZLd//LnHV1k5zKNGir23nJ3H1eKNlPbJPJ8zjwFHEpbpWzyu/P7lS9cHtl4vvny58sl8uph6yw+t85svX6pzGM16Oh+Z+pcvDzooPU3WFOfLl/GCTOeBjz/QIEh3+NI2O5sFTE+0uN/gn+kZ4c2SVaZU0In2WjM8JoNbLXiiNXf5aS1fpD+7HLUecO0xuNPaM6waT5cjGuCxu0HdK+vj9UwharDqb8o3rNeS+1155dZcnVaMTr9LFVyrbtq94ZqM3Sf43gOe8HemrcqkrNyNH2d3m/I9fOeJbMofb8+HTQyf4fEtPF+0Kv7ZoFEpr2m3uYC+Bndj5wFXylVWc+9prx1cVEbxd3ib8O9Z+HPuqv2uIbv1YN3vlL1+rx/gyfXgc4f3MVi1VVdui8/at6xX5u2k3m9ddyrGLZkE9X6vXSZjMm1M3Kd+r+FfVsoPtHc9IFob5m9MGnXx+YzTLXm/Evbj1psG7+u615xcVJpAJ3fT6V4XtNFs9tPjqLdkMha0nfF1aHyUBw2/sf+dGuj8SnmIu44SzvHsMTWWWd8/m/bUkCbQhrNPH+MjVpXlXdcYwXhnfZUGsFaji+u9Nvb7LJ7j5q5HmxjWllYai0bNgX/LTxTa5fxExlWt0zXWMPcUvcKfmB5dRR6g8Ht8zXbaNG5I7XFGK8NVv0cGd+pwSIIlbdQXg+bmDOgoLxof02sR/qDu3eACaEXqrnw5egT+pTKqnNmNj+cDr75O+r4cBU83E3eBz51Nu6usaX00DcfSxldVebZPl/CH5fS3w0c3QOvRTZfzf3XS7wxGjVHZAhkLyATGWy8v+t3qE/Ap58eA+OVhxA+ru64SXPr58wn5oxnQurvBfnl813186t/EMrP7HblVGTyHHo3T6eF+G3rA/AT/vxUt6Li6iWUQj/sPXM6ulXLjMmhrqNe+R+c0oNXt8+tJcIVVOsP+cCb4srpY9zqjPBkRsifmNgI5HtuDzzfyAHN6Jrprd3w5Y96RtVvVXfXPlYBorWFfvZ02K80zpolxOaBTZFS7HYi+/DJpTJbbsfUU0vDLI6y6T9incgP0MwJd/Sr0TH9WcxdEvX3O3GK9yGU9+t0Y443hRp/n0DVaNzHXM2d37S4D8fsnLjt5c/OAX3PWKdFRsN4Bvq0CnatLrLmgW6H9SE66T1Wa1+ZNtyrfqYMBjv6FefC9L2AVo3XH+acyFPx7DXx/3VUeKOheWK+zhj9YXdzbs8+VIelXFrPPBesRyqoypLXW9DJoKXcqzFu7muXMo5BWYl4dPpeonRHdwPzWRFk89jpGF9ZYgb3gFvabZWY/3Pm5i8bPZQTxeQTlIZm0gotsu5ttu7my4eR8FuB6K3jZvAKwPZQyHrfL0V54vM8U//Y5n3eO7pe3VA1gnYedfo8OybgNaw1j6IH8dZ3VC/dNwR834+qy30n2TfHZRZ7c5dkn42j+4dwTGyNer9x2asG4URnGvL/q9FqfaPdxcaM1q3w+rBPy7UXn1XXVCsc2TQ328E3Z73fdFdg76363NeuPg6AP+gy+M+zXroHP9MFdp3yPatUV2J18j3jgvMd1VB/aIHVul+qrhl/Mt2DTyBT21EatP+Q8VqQbUryyN8d2LbinNbBhYb9gN48x3RbCBvuoD2I9T8egN2rOhnG+DNeKr1PMN0KvudAG7CPN/sfHc9RtCd656zWNz4nNtxby9fne/vUisQ/Xg9AOBV03EfbrA5mM+FrLZOIGF52z3z5vysI2OjLWaZofrrvtUUfI0jDWwYLnsdY0LiNevNzambn2Lqw5yAidcT3gcloE/SEZNQ3Q4fEeOLqsnPlZOgHP1zPzKurjEF+JfY+P1XPXPvC2FfO/1xvM9nitVh0B74wa9fZDox6ArDQ4vbdzzuji8gbWUCFjWOd6U9nuh7t8AvtIrSrzswodOzPg4XK/1m4KGTpvz6LzE+jLkZ3YV0BboOevYl0Semztr1CvyYuUnZ/ofpZj6+/Ng5/dJu0hfPbUUV3jImxvdoKemm3XIsBCz7ry4OJJTnRKij77ujXHDsizC/fHCmsS7ZUHeC3ph8urd/1f/5U5ss/mjEzHMz9gOTBSdOgP0KazRPM8oEl8Y4EeWJstVsHyZuqiuc/hjEPf3ftWFkWIQBbHVGTHMSTFYrqkO8yTHI3Ikm5YDqaKjQhDmVfXzB8M+TjlD3IBAOPw/9LPEshOnPWfB9D4E8oeObJzOg71gIIQ0qTT0mS6LDHqL0vLISsR6L60mgRssShtpqvSaDJdl9ZDtBR/oTkr0ak/GWRGSKZBiCP/r2pVhv8KaGoRC5m6rEnAQ0zSdQ1oajtI0hxNU4hONZ0pL6GpIstvQlL5BSR9+LCHmGdJVEAbWaFYI0jjACCVdGboko2RJ5kqRVixqKNq+qvT5hvS5W+IUoFFC7jvz9If/I8/S/+JxtPVZPl/DrCUDQxVrRaQzTB0k+qyI5mEYUm3PVNyLNuQbNNADrM8zST0vZDtJRJ6/ojGs4D9XkroF3pXSp31dJ6d2YlU0yyDOabhSMTjzEZ0zJ0anHREY7Ki2rr5+oL4Qqqpr0m1OkMBKLDS5ykHkUv/qcgv5jzHs03HpqZkMwTbgq3aEmYekmzPNizd8RRVfTc01F5AQ+mt/zuyi9hFu4humZpnwFYsY8+CnRnpEpINRdKopiqMKYgp70bk9RcQ/mZaAq4toUnJ55z74CP4fbMccr79dFM/b5dgr4anqFT5dHV11vpY+o/AHzH+N3w8YQFwtz9ZltrC2/S//1FaLZjY3b1pEEzXvBk0H6zGbLJc/P5S7idMMTWLu1FtDUm65YDyIJYpmbAAtuWpmq3i97IIxnMWITQMW5Fviq+A+D3ddrJa+xol8z3u3r4Jp5Y7xGjvNxj2iAcsTGxJVxkoFVshkmWaloaJzjQnO4JTiKlqr01L8+toeSZ2+0JqZhyxJ5FPw54M2liTVGoCLzpUlmygmWToyNMVHahrOe+EfNbp/tMa7+qoEzWkgEpMpMmKLCGiqHBE0VQJ+IlKpoEV09GwrObY5IcoEPtmc43nMDSg6IQVT9U+ZaqgbQI0WzCaP9vTJrbTdvzrljOzESAMU2SZlipRU4dTiMYsyYGmJEORNQ9hS0dEy40A2QlNEZ+/bXyHVpJKNbYsiN34boM8bAvJimZTSdYdMNgJKDyk6lSyHDj3IM12TCdrNkWhO8zWZM0gsHA87kGxFDC2dCJhw1ZV4hGZeYVxD68a5HFQbl8e91C42uK1Hyz4oTKds/cQAXHDPUYcIRzIF6Tu+rgW3DdqrcVdr/UkEOHzYAWfrfrX8kWCitWTiAgfq86ice7q/W5LobXbaYLWpVD3yEu5Ybc0oOfVTX8zCNFVP+t9Dz8/NdKBo80FbYyCURo9/pGRceF9y6LTq2s1iri4kQdXKW9uHtIZrlUL+Kbd6gMf3HVpcFG59q/rS4G4e531gHUdpVFrP4Re2uGQjm8Hd13DiLxbT3yMp6HVp3g9sh4O4Nsn+jGhSQqV5mvG+Wz3szxvwZn86eYsjdrmItOhJ1F/NfrR2nBGNmX+Y2DN3eyN/wb43j+b733mFnrux1hriAgJ7onj3s6rm8UAdc7sfZoYH4WX+CN/tph/fTTEcB91d+XcdT3mqUrWvd7e0O6ttYuYx78TrT2kXC+dP86Idp14JD77ZS6Tu7w+PSbfKOUt4nKBu1X9tlbd0PM4uqQoWivT/xrkXSYb7tU1AropX/FohUT+n7IyuvWWtBQyafJxX/M28iOm+g9AnyH31F/U+0Pix55IkK29tT3Ok9t+lyrhkQLAj0wNwii4cXVBu67DYL6hl9q47PcCp3Ff6Im9hzXbcDoKulWMK/h9Qmswzk15TidnsK+4q77WnjYqi8GVf/Yr9+azKvfAt+PvPisqgPB+6lcr7v27SNGO7yuoq1Tx+Hra3KwnINeTRoXMcj3JYT+p8XN6NPxnRGGk359/7oh5w/zPfO45PKa/hK6uVA95tFN9jPbplefVrgv6PkXeqfQaiYiJNsjwRYUsgE4iEu0irVMykUdbb2K0Btb369VSKTEcE8FhB9kmWN8qlhywkiTLo4RqFhyI2IuOyn9lr5apI90wZE1ykG0ATU1TcgxmSqbpYMdGGDskG7b+nXm1/uYXnktOBAw9WceOIRuSKdvcUWM4kq2riuTJhqWbtqcQ7UX+1ENUSh3YX0yjV8NpPOZhzWZEcnQdxI9iXcKOpUm2rWo20gzbtJ/n5HsFnEY5ZarHcJqTJvZMnEYjhBmG6Um2ozBJVz0ZJAyESybE0SzFsy2Z5OI07y1TRy9JJXjwA2XqIIoRYrIpeZbKITRFlTBoO4nJmMmaLCNb14pAHGAQ04FXZc/jrkcHOIXxVdUxc2wFNGdOXMV3BOLkLbR440fFb1632feECE3cJ3FiqLYMOD3wU8FtvzcEa7sZ9DV3AZZ3ldW5ddh64sgHefrroEh549jJGcnJm2kOqRzGZv9EpH5MRCoVB7mfD/QxTRcDxhjF7VfbDzwGNUJu9lGu4/H6OzlH68F1pTG99Ke/Xdysp73a9fziRvdz1+RYjH7e6XI7r2XYt1EnY0ch9RbPr4lQhFseLz7DnUEuTeN4TLfmAL/e8rY4ArPiJ1T4exrNc9XWmrBO5afuU5NeBpz+wIepeWRO5iEykUX5viKudDcnZovEhXG7vc7ZrzD+KPazfYsV4PPnxZ8fa985qf0jyEk4hqwM3o5d4L9+ENOjML9mZ6yZ9ePyWzimYnl+uXyHck009/5O5UhkX4G9zRDz614PepVmiGCJPKIs7+ehOwfmXJDjccra7vyclEsGeqlTnt71+kGjHstka8wRIRbmGo0a9eU+L/QUvVFdRyie4vQqjYN5BQm6k88/OTku4Y/INSmi05H5H+DtZYa3j6zVa/EIU/f1rtcbpPlmwGXjrhusuD7/5EfrlDePnnyQ5vno4f58hP2guUuur6Lc2yi/gdsjR2Qz5i1hy1AFd3keWGgT9c8zeTZpXVI47mRs1SivMMwp7IItUWG3YA8dtx0yejhXFl8nL++UfAsDa7eDfs1ZNbXrAapVVZG3CftXX02vv8jnUbh+y+GVVaMqZBVsIOCpiNeifprZPATFKbIvcjwjB2mQp0dFPmitNQRaQ98gG5MW8GWg9m+TvTpnP1wGrHe1ao+DDdgsn8moHfTHVQXXr6cI9kewQ35t1OA7HaNKei7svVfT0CuwhjNFaOOA/bbkaDDqwd7qG5/JGM4WsP93unQFfQTXKs+LTefFhD+h/VE85sbb5Z3m8cB+Hk6hjVhu9v3wfapWQQfE+ThcjkQb93DWCYDOoGOMJ6DXDHRFM24X+gZ9shS6nQC/0Jqd2HS0NgzCNeT2ecGe9e+VkxNpdDKfn+wB/L68C7aMPdWQVckwTCzppqlKjqLpkq1qlk0MTVa9nzkzcYMneheIYhoKcYikKyqVdGwDOU3TlhTLYgqVMVaMLNT2vXkXVgsW5oa8TlKIYmvEIjxW0MKypDMKNLNtInmK48kqtTzT9t6rr+E0ip09ID/gjZfiKNtFCXlLNi+tFiLAOwwe/730dyCtyID4+z+2v4dRuH9/MXk9k3oOUNYEEQfymrqEqKNIVDEcbNkIGdbLwpXfSfbIu818UHVEmOYZEtU8T9JlBzjcMZlk6bZFFKLJ8styEt8+2enVPGgaswzmMSZ5NnIkXQedaJueLlHDJLpJCEb28/IOXsGDpp0y1WMetJMm9kwPGlJtg2IZS8Tm/IJhP7aRakky0hxkYV22te+j1p1Rkko3c0R/KB8aMwymqI6keB4suAz/szHItkP4BqVaDqJZTo7sLAcDUxAiOczjq+PBOnmI8gwcSmwNIUfPvvod+dDyl1q889OL9tOL9sN40XZiIR9wVxni8bbyXarqzH1c+a3hrwdYc+WdinPeneos4TS96ldGg897fxu3WH58oKq7uYBnn/zyiiOqefG+23c46n7mN3rtzV23HYTIR1hprOg7Df858ZfVe4F2uNG7cQWvES1E27bxpMe8dkGZ8ycdu7dkXB2FFXpC71XsxcvOfxeVSY2tcs7jWhVcWz8rVvN0pLa64PGt/fooRhp4BbVhOIdbXr1k2K/dvkq1nEOVtGgNZIBXhImrdIVzzvMI5b8DvM3XUaBWH3PQl1x52XqEc3h6x6tXXK2t0du2sevlAnmxgWbPi689XtEwrri1utXKC9S7noL+00B2p8CnuNcpW40KGTQ3ZeeycrY5EHsbx9fzPrZxwh/Xg6tO2fa2NM6t8rRTxS5nfsXy90wUbI1r7pAjwBzd6vcavKqT4F0sKl8JhHiCun1Ys/aUV+IScdn19sPBSnVh/0k8bX9c5Qjei7wHb1kV8TCKeLqME75fcs92jXtNeI5DdRV7kTkC2leDMa0c99KdIuPhmPOrJobPRPz8TtW+JIoijqDgsukmz+WmcVNzYI31vaqahX3ve59F+yA/Qt++JY0FehxWdg29GMlYhUeQI7kBUfUJ7McB4zkzr03vfBk/6Dk9Ip8y6JPJdi2eX20xHFt7SMZxNcxGbhuiil2xnsog1bn7QKj/Y29LrJ94pcKjFQqjHAC+L4ANyPfcltzJVHWMeCrywKT2ie2zW2OIu7dJRT4eXbMdW+IF/GbyTjR3w/Ukr/QZetauBrCuQeg9EDrzHms8P6Elh3kuypB+nA66akTLODrmo0G/lU79kSOxdmh1eDx+Wv62Hp6TbNUj1eM+P+nTtO1UXGlPeIRmjY/2b1F+1ZGx50cdbfXzYBjJV8hb560p8N88J0ItqfK3rXa5/ubylBfRBmvxQLt0KiI/tNQYt95rYZt8K7lxe+XRHdB1z9v/cpou9nX3oUqLOz/bSIh8OUz2Zmg/qXC+w9v+Oke+12EFxa+KlNifyyEZL5K7RP6LZfqoTRtVlHyi3dY957c+twnh3CVsMOHNXu7sJZF81KMIo2I+g/b35lcY7RDKRFKpWczn+Wc1ys8ZsjjbumGuG9dJO5G3ydmkqa0nByrJ7rWxYz8P4Vy/ecNK4SKqJPL4P/AcxjvtOj7nggw6Gx4V8MkvY/HumO/pLm1Ul1FV/ce40uSvQAc7//ND9t0p8l5g98S6VlnSuMq0G437c2pNuk9lGuZkytOLzutUwo/6euF5McQz+LjeoELwKWfFkD6dMtcR029RKT+XXv5z6VX9NvTq6lF17F1avRUfi3NgxK9fU0l/h6eO6pm9ft4MUys4C4ZYoPvuq+vnnfsy9Iuq5oNdfVo7fF1D/eq6J5//CuQrfQsK1707OjAjO4kOzO0jOcPF423GN6dE4xW57VHV+wNnyQgLdDme7+r8XbC/m+kq/hfZMRfh9NwWE7cSpL5XcKaM+KszErjT8XFE9sJ5XC06NYbobFB4pt17Hp+Rn4d1vtuz7Ffo/mefXZ/jfzjlTPeNznJH57l/tny7+X7jM2yEFUXyFMrStToM7tRFTgZJONckCjuRpdgvlHfuSuT4jXw9zzjHRuMX0aYiyjaaz1vaTUW0PcJPO+e2/XPt2+qpvT2O03gH5w2zSEBvQZ8TFN40kB3j9gz3xvbWdp8T/dy2A6DNDNev+A1gIxhbdBZvOw3YPwp5gZ938s6o1b3nKRsibnN3zwn3ttT399be6zTy5vd1N0fcpnyr/jre58+h/yECngVeCnk3v87T8f5P0UmvN45jWMNDf9wXN7QdXLco+ybf9nCFD4PfqtLvDcWtKn01PCcXrl3cXsaOCNvqT5oPcM7IwS3Kt+JWqsieQ7DHx75p7qsi9ebDnery217A3ioPRYZWvQ1/F0XsH8I6crM94syIbSzEDa8JVb2/6xr3/e5jJKeNE+oApWTObQak58Ja7d8sWMBH2/pWx/b1HF6K9EO83xX50cPMx3CNO/1eVQH9Jr/l2Sjcg5K6UTyrLtKTxkMSkyGyeuhDaOO/7Z6z62/fs/e5XzLq+3bsPtKu+7S9TXAw8SpkJubKb5asDNciW6d+lmTdXnR4zEt1A+tuFJwXElsbqyChYMfG8Qupc8e6d/jcwu3dAAENC95/yn0/xMtcnvlTiJnWnHF/DDb3S+JcXtonrCXIN2+zECO+5nYbzDc6F/lfqyeTm/BinVOrPjVqzaAP+i6TvVhrgU7g6/74LXROrN9+6pyfOucd6ByB2cX2xMnxG9wm2u3vCA6zbT++qS+miah7J6ocFNw+db0zr/3bGIGOfG6gI4YpjLyZjxt+rX7Nfz+OT0iNoZ17S2R8Y12sD6+LblJM0adVUAP02Jl9Z41e37d+dC95Rf/6sZvT9vaY1/erA++CnQg65VvM9ZA/fYfme/7fnc+jm9MSmUvwwdf3N1i7/NUf26vwfBSeCTguAfq7MCt85924yoI4D9yJDOhHOMtG/rxEd6fOETt7+p1aXcH6L0CPjg7q+H+HjbRDT5dnMRf70ff00nP36G+N3+zKxH4swo4sRrFVO989GN/xdb5gUT1ghIuxmpTe/slz75HncmNevkLvXVb29uvd2s55NodLarwmtrtX+/oreX1vnMdibo7GvZy27+7adKfFuxyP8znOKwKXz9+LT+j759k13FczsUSRfcrxvgx/x7hc3n4a4Xk765aOP0rx76HqTsfPwM+uP383dh5wpXwsTnd7M3sYi5TxbaICn2Zy83VBvtYpt7Z/uwpwIT4r8l0y1dqqSbW2g77vWuEZKVtZLkgqyxXerhu2eeItvts12PrsKwf963FsFfdXPL4iP+XaK8+8v6CAt8RdEBuOcSCQtS2PFtxrsJWZWapK40r4aiaty35vNN3pY9ao3I3376dYbm+Gd+Gsec/j8jiWEIBcZ2+636VHdAN17p52jB4Cz789dCN1yK+XKVm7PCEOGst5dyykaBfG+YyBX5fHqw6GY0mfcfJvm+Yy2t9gVclWlbqN4gI/rp2tLD3r3JQdb9AMYI1Ufq/H1o+ZKw85leKK8j2K8bPMuqX45/Km6Pbuswz/7PQXYnw1J11ttJCPn2Xf19sPuzQL4zvCNe11xB0QwzSfvzbdMnMT92Hs8XnBbeRbuuWN6furtuQRm1qabkuEGrKkIxVLyNOZRHVN1ik1CPpZbSlp8MRqS0xVHMRvfbcpr6yAZFNyGK9gpVmGRxRTpdbrX2v6rastLXl5hbDe0mrB5rwMw5+lP6Yer5xARd2gbQmm0v8r/bFGk2XmwUuLB5nMNhzT8iTGLzvXHUOVENY9CRFGDF7dhjivX8/qG1I3uXq6VNohdPH100DgT3jhUx9Nvu5Ob1MnhmUTfqsLrxZGNSYhlcqSYmCZqQbV7fdzgfxfqDiQespU/y3FgWybqjri99QonqQrjilhm6iSypApY8awgr+P4kBqSSq12Xj68CNVBzIRs2XqUYl6SIGNiCAJ2SaVkKFiWVYdQ9HMoovpLd1TdWpLusbvR9dNWcJYMyXZZPymVIrknFe/o+pABWstXvrBygO9gzo+bs3VacXgeIuCa9VNuzdcw7n2Cb4H5ztxF1qrMklq8NzDd57IhuNnwyaGz/D4Fp7H57DymnabC+grxgCqjPvU4TxyUXjnoCvOG249WPc7Za/f47b/fkxFW3zWvmW9cpDBMApr9TRybqkQn6dxlrx6PHEuZUEbHPtM3yuX+KVncZ5D9r5DgVscwlvyxrJToyRbe2gnNzA9r92cwggH4j7/nZoqQWuN4Wx1EcZt8/jDDY+dYBtxv+CAx3hcpWvThHhAjCsl9yJ+rpw9NuqP9pYORpPIPO7k8TMZuUtSbxtx7lZentpLb8XI1uA4H2xzC4tq6xyJ983eEVhc0+XknDOe53LCHYfPy7fkchEQX9QVSmq0cLwrxDqOYsi5fqEM9vAmtUX2b4foj20Rm5VXGfsr7qB9ndohJ9DrIOaRG08W6xEukyfmf9WfV+sju477Omo3bymKfYnr5hTcclKO8Pj4hhQYe7UZ9FVXvxyFeHuE1ZRhXbZ+t/Mz/6Ki//fnzci+qD6OLjajXzNyGeqVGB+/iX0vp9xiEuvb7xav74h+03Q7ppOO4bvZGgDfTS5UiGWT6AaXLb4f8pvQbWE1/WxuEMh9XM0/8Tvl3toUtbPF7gef/bP1CfxW5DvcryJfGVqZ8dcV/ULESHL7yA1An2z6fIw8h0Bg4XKcH+I0tasj1edfxm9FenOb25CJFxriySh9g8SM+x9RzZ2RlE/llfbbr8tFETx4rLbGdkyiBkbCI7s+L9jXa1WZ27MiZjDFe1/ly+qs92/JKrKPE3vrCN5/im0R2Z90DO/Wqj6uuVve7+yuY3y7R3E8aK5snvM9YLC66QarC+Cdu26wuIPzQD/JDyuWyWR8+TfpJHJyfcBnEtcHyGnDBlt7/SxfyP7d8p2w/9uY1s/ID0tshyNzOOBr/Xj2Hd8agRzbcgzFlmzDVDnmbkuO4hAJYc/WLEQUD78IEf4r+zFsYmLPVD2JMQVLuowtydZUTSLYtimzdNt45kXD79GPMRdAUOjI4CDRn691f4RKiA6MhyWmcc+aY1iSo2FPUjRTV6htGhZ+/Ru9X4Vyrwalq8REmqzIEsgfCKXBL9PwCJVMAysmEENWc3jve7ip+qSJPRNK93RDRTq2JUx0m7eJJMdDlgTaC9lUxVjfv9v83ULpZkkqVabw93xZ+hTQAqz8ewLVk+tR4Iv//Fe+uFMqW5bBVMlksiLpigd7j04syXMMk1BmOEjP8nok0pasvnvA/OiKitd/MOj8Z2X9f0dl/fA+viqvtrzop6sXjoOAbIqzmogCp7f75JT0a4Kyi2ilxxnRrv2i6OTwpNRKkKqrFDrGI2z73SpHpKZijNnTn8iyv+PIrPo4Sle7QF33FKQpU/FfZK1lTp+HKvim20giNbP3GIZIoIh6yr2/eRsFuHPiiZGVHVRx5+QYIVfFVZa6eW0ZNzTMgOvx6m6wbrunUTO/Env4cydOqtBmfp/HEKwQleV8K79B5ty3qkp7NGsuzDbsn2fm+MDHQybtvYjRXVQhvq9SRDlP4jkOHq8qo232au5Jm1dxcoc82voiRPdDFFVUfMobz/PvfQZdBTLN782kx6MVOwb//cXVZvP7ilAM0XZAG5VFhLLKB+TgLDll56MCBVXfCnXG3ruiGh1fr/1I2uqoXwmjUsXdpQmCaXRBXx2szpo3zoLI0a9H1ArG//Ksjqz8iQhZ4YnZosiF2TmjxweuF/pjm6Ove7o+zl4SfB4h4XGVlrA6kAx8v63Mc3EzHTA1R/dpcr5HKNqLLjaLU5HMNFosMtp2ZVncEiPkHewHVU9lucWZcTzLrWzB37yilbOr+/keFlefitDle9A5PAMKeP46i8wWZZLszgH0JtCR2wjHdPXHuK/9Kslbj9OOXN5EejPZN/ZRuKN97e4/fO98kW4ObRnhdXmKvF95ejX0kFfIorlJe6wO6NCo3RNsihM9aluPHOwbZw1/SPqVxYxVH58uKvr8onOowuyRTJgjumsfpT7BQ+YWech29fm+JzKMxudtR2Md0Q30tybKYtNL9ODJNw6cnOXx0v0GFejvuDraQZQ7pPeb3EePXhy9f3g/SY07H6XetUP3vCkz5/tBqxXTI5ZCsGQgTefIqiI5CkMSo6Ylm9Rmpq38RKujBk9Eq3WNqsT2qMQsi99rSplkw5FWQga8g3m8uJmNWPzO0OpPk2BTWi0Y0NNflEJIp+R7goD8Xl5BZz9GZ0rscckmHCYqzeb+dF5aTksPH9QPMNeXgtoMY89zZFOSHYQk3VRkyZGJIumabRk6tk34/L1eivxqsLbHPKzZjEiOrpuSTrEuYcfSJNtWNRtphm0+0y/yXmDtkyaWB2uHv8R9hcj0XvNZuPvZoDUOpmTE9UMWtY7plwclF40xCpQuHOViuprnwJRyAWlnbD72l0tG+RhCVDb3cQHlr2Dl5wgGvPiloINI/jTDRKqOJNskBpc67uG0bEnDyFINzXNMfc+pdASqP6M0G+6+la0MYO5PhHsgZwnGIVYp77ObILFwsyFKMx3N2YA9nj/OAp/4ywqaLVfzvK31F1h4FCHKe+37g8l0zsrT5Rkh3FWXM6zwK43JkmcoBXmNw8os/MWywhtg8wPf4AQ88C2CFqzDte3Sf8idxSCYYhRUptOATteZuaxE6/nPTnaVDEBXLG9CjZowar7P6c3ZO4d5bQvJimZTSdYdLOmE2BLwMpUshxoUabZjOsozmLfGlgV0eBMOTrbVL/Mvk7/xPLbFT27+C3MzohghBqaQZ6kMVLGiStgEvmYyZrImy8jWtWdwM3z4jVQxLA7vSLAx/P6Tif/KTPzM++OPMHH+netvw8YiL1YwcZIhK/4iaEJYcJM8RYSw2VL8/ZPV/yqs/iLj+rnpkkeEoSid9E2kYRvG9pPJvz2Tp86Wa4YXcFhlyw6bP6Q4dvuwEvjQwf7DpT+Ov88/CaXnF95GuDhKOOpf2ONsOgeO54FafNjyB/VDhDn8MvYn/ng1dpOXwqcSZkv0wQQR+Nf/B1OEwf3s1QAA
```

- - - -

## Installation

1. Copy the import code from above and import the content

    ![Import Actions](assets/media/import_actions.png)

2. Move to the `Commands` tab and enable the imported commands

    ![How To Enable Commands](assets/media/enable_commands.png)

3. Done! 🥳

- - - -

## Commands

- ## `!ADDITEM [USERNAME] [ITEM] <AMOUNT>`
  {: .no_toc }

    ![User Inventory](assets/media/user_inventory_add_item.png) 

    Add an item of your choice to a user's inventory. The items can contain spaces. Set the optional amount in angled brackets (e. g. Health Potion <10>).

- - - -


- ## `!REMOVEITEM [USERNAME] [ITEM] <AMOUNT>`
  {: .no_toc }

    ![User Inventory](assets/media/user_inventory_remove_item.png)

    Remove a specific item from a user's inventory with an optional amount in angled brackets(e. g. Health Potion <10>).

- - - -


- ## `!USE [ITEM] <AMOUNT>`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_use_item.png)

    Use an item in your inventory with an optional amount in angled brackets (e. g. Health Potion <10>). This populates the variables `usedItem` and `usedItemAmount`.

- - - -


- ## `!ITEMS` or `!INVENTORY`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_items.png)

    See the content of your inventory.

- - - -

- ## `!TRADE [USER] [OFFERED ITEM] <AMOUNT> | [WANTED ITEM] <AMOUNT>`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_trade_item.png)

    Trade items with a user. Only one trade request at the time. Amount is optional. Example: `!trade tawmae Health Potion <10> | Obsidian Sword` to trade 10 Health Potions for one Obsidian Sword.

  If you don't enter a pipe symbol `|`, you can gift the item to the other user. Example: `!trade tawmae Cookie`.

- - - -

- ## `!ACCEPTTRADE`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_accept_trade.png)

    Accept a trade offer.

- - - -

- ## `!CANCELTRADE`
  {: .no_toc } 

    ![User Inventory](assets/media/user_inventory_cancel_trade.png)

    Decline a trade offer or take your own offer back.

- - - -

{: .new }
Items are case-sensitive!

- - - -

## Example: Loot a random item

![User Inventory](assets/media/user_inventory_loot_3.png)

The previous versions had a dedicated loot action. This one doesn't, but you can still achieve that. For that, you can simply create a new group in the `[User Item Inventory] 1 - Add Item` action and put the `Set Argument - itemName` subaction in there. You can then duplicate that `Set Argument` subaction as many times as you like - each subaction will be one item.

![User Inventory](assets/media/user_inventory_loot_1.png)

You then rightclick the group and select `Random`. This will pick one of the subactions at random. To specifiy the odds even more, you can rightclick the `Set Argument` subactions and set their weighting. Higher weight -> higher probability. 

![User Inventory](assets/media/user_inventory_loot_2.png)

The `!addItem` command is not affected by this. This only applies to any other trigger that is **not** a command (like a Channel Point Reward Redemption).

- - - - 

{: .highlight }
If you used this extension prior to version 2.0.0, use the `Convert Old Inventory` action to convert the older inventories to the structure of the new ones.

## Changelog

| Date        | Changes          | Version |
|:-------------|:------------------|:------------------|
| September 8, 2024           | Complete overhaul, added trading | 2.0.0 |
| August 16, 2024           | Updated to Streamer.bot version 0.2.4 | 1.0.0 |
| May 9, 2024           | Changed the global variable methods to userId instead of the user's display name | 0.2.4 |

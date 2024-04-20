# 2023-2024 NHL Playoff Predicitions

If you're here, thank you for reading! I rarely do any writeups, so I apologize for any grammatical errors or tangential rants I may go on. Thanks to [Bennett Summy](https://github.com/bsummy) for creating the web component of these awesome team pages! You can view them as well as other player advanced statistics and video that I have aggregated on my website, www.pierreanalytics.com. Without further ado, let's get into this.

## Playoff Predictions

The day before Day 1 of the NHL Playoffs, I ran 1000 simulations of each series based on home and away probabilities drawn from my gradient boosting odds model which use the following predictors:
- Home and Away ELO (Inspired by the folks over at [538](https://fivethirtyeight.com/methodology/how-our-nhl-predictions-work/), great article)
- Home and Away rolling EV xG% over **five** games
- Home and Away rolling EV xG% over **ten** games
- Home and Away rolling GSAx over **five** games
- Home and Away rolling GSAx over **ten** games

Separate write up will go more in depth to this model, but here are my results.
![image](https://github.com/neilpl24/2024NHL/assets/59701044/b4f2b7a6-d5aa-4ebf-8366-c0fb8005512e)

### Carolina Hurricanes vs New York Islanders
|   CAR Team Stats   |   NYI Team Stats   |
|------|------|
| ![Image 1](https://github.com/neilpl24/2024NHL/assets/59701044/7690a1a1-8fec-4c46-9cdc-68b8c82433af) | ![Image 2](https://github.com/neilpl24/2024NHL/assets/59701044/adb2d7da-ff37-434d-9c04-b814a9aa9499) |

![image](https://github.com/neilpl24/2024NHL/assets/59701044/e24a071d-7236-494c-aea6-7c26968b716a)

I have a very big bias for obvious reasons, but I really do think despite the Islanders hot run into the playoffs, they are no match for the forechecking beasts that the Hurricanes are. The Canes are going to dominate possession and I think the PP and Guentzel/Jarvis/Aho will be too much for them.

**CAR IN 5**

### New York Rangers vs Washington Capitals

|   NYR Team Stats   |   WSH Team Stats   |
|------|------|
| ![rangers](https://github.com/neilpl24/2024NHL/assets/59701044/f1c7244f-1745-470a-8ee8-321d193a6e3b) | ![image](https://github.com/neilpl24/2024NHL/assets/59701044/e49582a1-24f9-495f-8977-4460d0a66a77) |

![image](https://github.com/neilpl24/2024NHL/assets/59701044/84be820a-8a89-48a9-9416-db1fd63fcf13)

The Rangers strength does not come in possessing the puck or outchancing the opponent, but actually comes from an absurd amount of talent they have, finishing and goaltending. Good luck Caps fans, Charlie Lindgren and some overtime luck are your best hopes.

**NYR IN 5**

### Florida Panthers vs Tampa Bay Lightning

|   FLA Team Stats   |   TBL Team Stats   |
|------|------|
| ![panthers](https://github.com/neilpl24/2024NHL/assets/59701044/907920b4-384d-4f69-9046-36685452f3c0) | ![image](https://github.com/neilpl24/2024NHL/assets/59701044/d4a1c4cd-339f-480f-b0b2-33126a44501a) |

![image](https://github.com/neilpl24/2024NHL/assets/59701044/38c6867d-ad76-4abe-a280-ccbeab861d15)

If this series is anything like it was in 2021, it is going to be absolute cinema. These teams hate each other. Florida will win if they stay out of the box.

**FLA IN 7**

### Boston Bruins vs Toronto Maple Leafs

|   BOS Team Stats   |   TOR Team Stats   |
|------|------|
| ![bruins](https://github.com/neilpl24/2024NHL/assets/59701044/633a48c9-dc98-46e2-aa64-0f476b842465) | ![image](https://github.com/neilpl24/2024NHL/assets/59701044/1a2b2f92-e463-4554-ac34-17a77a98c8f6) |

![image](https://github.com/neilpl24/2024NHL/assets/59701044/0f059461-85a9-4a6a-8c71-0af3a3cd0289)

I think this series is either ending with Toronto in 6 or Boston in 7. This is the Leafs team I've liked the least in years, so naturally they are somehow gonna make noise. Going to need to get past the Bruins net though.

**BOS IN 7**

### Edmonton Oilers vs Los Angeles Kings

|   EDM Team Stats   |   LAK Team Stats   |
|------|------|
| ![oilers](https://github.com/neilpl24/2024NHL/assets/59701044/e33f4395-a3fd-48ae-935a-deebfc248f40) | ![image](https://github.com/neilpl24/2024NHL/assets/59701044/b43257ac-9181-4740-b307-328964022876) |

![image](https://github.com/neilpl24/2024NHL/assets/59701044/824d74e0-3409-4a6e-8c7e-58b89124b523)

The third straight first round meeting for both of these clubs. The Oilers have taken the previous two, but it has not been easy at all with them being down 3-2 in the first installment and being on the brink of being down 3-1 last season. LA could make things difficult with their trap, but I think McDavid and company will be too much again.

**EDM IN 5**

### Dallas Stars vs Vegas Golden Knights

|   DAL Team Stats   |   VGK Team Stats   |
|------|------|
| ![stars](https://github.com/neilpl24/2024NHL/assets/59701044/1415191e-60b8-4929-ab31-870e360d61b4) | ![knights](https://github.com/neilpl24/2024NHL/assets/59701044/1387b386-c620-4ae6-8630-731c2c2e6526) |

![image](https://github.com/neilpl24/2024NHL/assets/59701044/cb0547f7-c2e9-49ff-8d71-4131bb5acf46)

Dallas is the better team, but I wonder how this series gets impacted with Mark Stone coming back, especially with my model having a glaring flaw in being roster agnostic.

**DAL IN 7**

### Winnipeg Jets vs Colorado Avalanche

|   WPG Team Stats   |   COL Team Stats   |
|------|------|
| ![jets](https://github.com/neilpl24/2024NHL/assets/59701044/c6365778-3875-4381-aebf-bd4755983547) | ![avalanche](https://github.com/neilpl24/2024NHL/assets/59701044/3d3db185-f9d1-4536-b91a-2bc9b6edd353) |

![image](https://github.com/neilpl24/2024NHL/assets/59701044/06e4b56a-e3f7-4f89-8818-be10beecfe56)

Colorado has the edge in possession metrics and special teams, but they will be without Drouin which is a pretty big loss. Connor Hellebuyck is the best goalie in the world right now. Confident that if this goes the distance, the Jets will take it home in a rocking Canada Life Centre.

**WPG IN 7**

### Vancouver Canucks vs Nashville Predators

|   VAN Team Stats   |   NSH Team Stats   |
|------|------|
| ![canucks](https://github.com/neilpl24/2024NHL/assets/59701044/6376b864-484e-4dcb-9283-67ff1064cab0) | ![preds](https://github.com/neilpl24/2024NHL/assets/59701044/c5ed1257-7685-4939-8fde-28b94f851596) |

![image](https://github.com/neilpl24/2024NHL/assets/59701044/559d9769-b1da-4d52-9aae-c33b6e17bb71)

The Canucks have actually done a better job of controlling play in the second half of the season after their insane PDO bender. Nashville has slumped a bit of late, but I really like Brunnette do think they make this an interesting series and steal one in Game 5. 

**NSH IN 6**

That concludes a playoff preview that will probably be blown up by injuries, a [bullshit goal](https://www.youtube.com/watch?v=BMFVCnbRaV4&pp=ygUYYmlla3NhIG90IGdvYWwgdnMgc2hhcmtz), or the lights being too bright for some! Thanks for reading, if you're still here, check out my website at www.pierreanalytics.com.













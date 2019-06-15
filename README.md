
`Judge`牌是由Los（_Los）自主研发的一款休闲类卡牌游戏。

------

# Judge牌说明书

  Judge牌是一种休闲类卡牌游戏，适合2~4人娱乐。在Judge牌中共有11种不同类型的61张卡牌。每一场游戏都会在牌堆被摸完之后结束，且积分最高者胜出。注意：玩家的起始积分和下限均为0。

## 卡牌介绍

**AC**(12)：使用成功后使用者会获得3积分。AC可以被WA抵消，且原来的AC的3积分将转移至WA的使用者上。

**WA**(12)：可以抵消AC，也可以抵消他人的WA。

**TLE**(4)：跳过下一位玩家。

**MLE**(4)：使用者从牌堆中摸取2张牌。

**CE**(4)：使用者用一张手牌与任意一人的一张手牌交换。

**RE**(4)：更改游戏进行方向（顺时针变逆时针，逆时针变顺时针）。

**UK**(4)：可以抵消除UKE、Coin以外的任何类型的牌。

**UKE**(4)：可以抵消除Coin以外的任何类型的牌。使用成功后使用者获得2积分，被使用者扣除1积分。

**Empty**(8)：空牌，不可在出牌阶段中打出，只能在游戏结束后兑换积分。

**Coin**(4)：使用后可以立刻获得3积分，游戏结束后可以兑换5积分。

**Judge**(1)：万能牌，可以当任何类型的牌使用。在游戏结束时可以兑换3积分

## 规则

  游戏开始时，每位玩家会得到4张初始手牌，从某一位玩家开始，逆时针进行游戏。 每一位玩家的回合依次包括摸牌阶段、出牌阶段与弃牌阶段。 在摸牌阶段中，玩家需要从牌堆中摸取1张牌。 出牌阶段中，玩家出牌没有限制，打出的牌则视为弃置（即与游戏无关，不放回牌堆）。 当玩家出牌结束时，则需要通过弃牌的方式将手牌减至4张，弃掉的牌也视为弃置。

  游戏结束后，如果玩家还有剩余的手牌，则可以兑换成对应的积分。 Coin可以兑换5积分。 AC、WA、UKE、Judge可以兑换3积分。 TLE、MLE、CE、RE、UK可以兑换2积分。 Empty可以兑换1积分。 

------

我们选择`WPF + C#`来实现Judge牌的PC版。（正在开发）


# UEMA


Porting Unity's UMA to Unreal Engine


## What is UMA?

UMA (Unity Multipurpose Avatar) is a hugely popular character mesh library for Unity (a de facto standard), with thousands of assets ripe for the game making. You want a game with interchangeable armour and clothing for your characters at runtime, there isn't really anything a whole lot better.  UMA also has code that allows you to adjust these assets, like literally 100+ options at a character create sceen.

Luckily, the UMA skeletons seem to be built from the same general humanoid template as the Unreal mannequin. This means every Epic skeleton animation in the UE Marketplace can be used on these characters.

But for now, they are stuck in Unity and can't be used here.  Besides this quick proof of concept: http://i.imgur.com/HVVMFMa.gifv

## Get Started
1. Clone this repo.  `git clone https://github.com/zerosum0x0/UEMA.git`
2. Get the UMA content. `git clone https://github.com/huika/UMA.git`
3. Import assets into Unreal and get them (even semi) working, submit a pull request.
4. ???
5. Profit

Create an issue if you are going to work on a major area of this, or if you get stuck and need some code done.  The aim is to convert the entire system 1:1 into Blueprints and C++.

## Helpful Links

https://docs.unrealengine.com/latest/INT/Engine/Animation/RetargetingDifferentSkeletons/

## Legal
Disclaimer: UEMA doesn't stand for anything.

UMA is licensed under MIT, meaning you can use it freely, even for commercial purposes, as long as you distribute a copy of their license with your game.

Unity's asset license is generally permissive to other engines. In addition there is an extra clause (2.7) that says open source licenses take precedent over Unity's EULA.

http://unity3d.com/legal/as_terms

AnimStarterPack content is free content from Epic Games. The Survival game sample series also hosts it on a public GitHub so we're not treading new waters there.

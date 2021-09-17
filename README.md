# Naumachia
**Pronounced *NOW-mah-kee-ah***

<img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/5676e946-eac5-462d-8385-566c5e7b4794/d65jmrg-e27fcd82-88c3-4cc1-ac7a-b4894f31b516.jpg/v1/fill/w_1024,h_911,q_75,strp/naumachia_by_flaviobolla-d65jmrg.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwic3ViIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl0sIm9iaiI6W1t7InBhdGgiOiIvZi81Njc2ZTk0Ni1lYWM1LTQ2MmQtODM4NS01NjZjNWU3YjQ3OTQvZDY1am1yZy1lMjdmY2Q4Mi04OGMzLTRjYzEtYWM3YS1iNDg5NGYzMWI1MTYuanBnIiwid2lkdGgiOiI8PTEwMjQiLCJoZWlnaHQiOiI8PTkxMSJ9XV19.k2D97fOeDsw2DXHZMfp1aoofmjREDa4o-m-vO9PcM-0" alt="The OG Naumachia" width="400"/>

#### A two-player naval VR action game created by Team "Szechuan Sauce" C for the Games Project 2019/20.

## Cloning and Pushing this repository

Please download [Git Large File Storage](https://git-lfs.github.com/) onto your machine before cloning this repository.
Then, once cloned, install Git LFS inside the repo directory BEFORE making any commits/pushes:

```console
git lfs install
```

Please make a new branch if you wish to make any changes. The Master and Dev branches are protected, and can only be merged with via merge requests.


## Unity

Requires Unity 3D 2018.4

## Creating and Joining Internet Match

- Make sure the game is setup as a project with multiplayer enabled on our group Unity account. This can be checked [here](https://developer.cloud.unity3d.com/projects/?_ga=2.144945975.227170982.1585418529-1144442702.1582134087)
    - If it is not then follow the steps on [this](https://docs.unity3d.com/Manual/SettingUpProjectServices.html?_ga=2.144945975.227170982.1585418529-1144442702.1582134087) page.
    - Make sure to enable multiplayer as you do it and only request a max room size of two people.

- If the above is completed, do the following:
    Host:
    - Run the game as usual and click "Enable Match Maker (M)" (UI becomes butters here but cba to make a custom one).
    - Click "Create Internet Match" with any name you want.
    Client:
    - Run the game and click "Find Internet Match".
    - Click join when the room name pops up.
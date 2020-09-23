<div align="center">

## Kinetic Energy


</div>

### Description

It gives you the numerical value of kinetic energy. This thing is related to physics.
 
### More Info
 
If you like physics, this code will be fun for you

It returns the value of the kinetic energy.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jack Tabsun](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jack-tabsun.md)
**Level**          |Beginner
**User Rating**    |3.8 (34 globes from 9 users)
**Compatibility**  |Microsoft Visual C\+\+
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jack-tabsun-kinetic-energy__3-5109/archive/master.zip)





### Source Code

```
//Kinetic energy
#include<iostream.h>
int main()
{
 float m,v,sv,KE;
 cout<<"Enter the value of mass ";
 cin>>m;
 cout<<"Enter the value of velocity ";
 cin>>v;
 sv=v*v;
 KE=0.5*m*sv;
cout<<"The kinetic energy is "<<KE<<"\n";
 return 0;
}
```


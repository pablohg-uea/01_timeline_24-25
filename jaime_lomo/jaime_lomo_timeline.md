# Mi historia con la informatica 
###  Mis primeros
#### 1. ***consola***
Desde pequeño siempre he jugado con mis primos los cuales me sacan 4 años, ellos se podria decir que me metieron al mundo de los videojuegos ya que a la edad de 7 años tuve mi primer consola la [Nintendo Ds](https://es.wikipedia.org/wiki/Nintendo_DS "Nintendo Ds") ya que como ellos la tenian pues al final consegui convercer a mi madre para que me la comprara.
|`Consolas`|Año|
|--------|----|
|[Nintendo Ds](https://es.wikipedia.org/wiki/Nintendo_DS "Nintendo Ds")| 2011|
|[Playstation3](https://es.wikipedia.org/wiki/PlayStation_3 "Playstation3" )| 2013|
|[Playstation4](https://es.wikipedia.org/wiki/PlayStation_4 "Playstation4" )|2016

#### 2. ***movil***
Para ser exactos, el **19/07/2013**  a la edad de 9 años,  fue cuando recibi mi primer movil por la comunion,este era un **Alcatel** el cual no recuerdo ni el modelo pero, tambien recibi mi primera videoconsola la [Playstation3](https://es.wikipedia.org/wiki/PlayStation_3 "Playstation3" ), a esta si que le meti mas caña ya que algo de idea tenia debido a que habia jugado mucho con ella anteriormente con mis primos.
| `Moviles`  | Años |              
|----------|-------|
|Alcatel| 2013|
|Samsung Galaxy j5| 2016|
|[Iphone 13](https://es.wikipedia.org/wiki/IPhone_13) | 2020|


#### 3. **ordenador**
Despues de comprarme la [Playstation4](https://es.wikipedia.org/wiki/PlayStation_4 "Playstation4" ) unos años despues de la [Playstation3](https://es.wikipedia.org/wiki/PlayStation_3 "Playstation3" ) me compre mi  primer ordenador sobremesa, que seguramente sea el aparato electronico al que mas horas le he echado.

![ordenador](ordenador.png "Ordenador" ) 
#### 4. **codigo**
Mi primer codigo lo hize en **C++** en mi primer año como estudiante de ingenieria de telecomunicaciones. Uno de los ultimos que hize podria ser este.
```c
#include <stdio.h>
#include <math.h>
#include <stdlib.h>
void monumentosMascercanos(char nom[][40],float x[],float y[],int n){
	int i,k,m1,m2;
	float dist,men=999,dx,dy;
	for(i=0;i<n;i++){
		for(k=i+1;k<n;k++){
			dx=x[i]-x[k];
			dy=y[i]-y[k];
			dist=sqrt(dx*dx+dy*dy);
			if(dist<men){
				men=dist;
				m1=i;
				m2=k;
			}
		}
	}printf("Los mas cercanos son %s y %s: %.2f\n",nom[m1],nom[m2],men);
			
}
int main(void){
	char linea[200],nom[40][40];
	float x[40],y[40];
	int n,i;
	FILE*fent;
	fent=fopen("puntos.txt","r");
	i=0;
	if(fent==0){		
		printf("Error lectura de fichero");
	}
	while(fscanf(fent," %[^\n]s ",linea)==1){
		sscanf(linea," %[^#]s # %f %f",nom[i],&x[i],&y[i]);
		i++;
	}
	n=i;
	monumentosMascercanos(nom,x,y,n);
	fclose(fent);
	return 0;
}
```

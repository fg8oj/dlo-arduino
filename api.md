# Syntaxe :
k= votre clé
Demandez votre clé à me@bdm.fr

## liveall
retourne les valeurs pondérées de l'ensemble des sondes (réservé aux applications autorisées)

/json.php?o=liveall&k=xxxxxxxxxxx
Retourne :
```
{
	"releve":[
	{"id":"1","val":"167"}

	]
}
```

## listall
retourne la liste de l'ensemble des sondes (réservé aux applications autorisées)

/json.php?o=listall&k=xxxxxxxxxxx
Retourne :
```
{
	"sondes":[
	{"id":"1","commune":"SAINT-FRANCOIS","section":"CAYENNE NORD","lat":"16.2564","lon":"-61.2856"}

	]
}
```


 

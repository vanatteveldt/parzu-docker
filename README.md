# parzu-docker

Docker container for [ParZu](https://github.com/rsennrich/ParZu)

# Usage:

```{sh}
$ echo "Ich bin ein Berliner." | docker run -i vanatteveldt/parzu-docker
[..]
1	Ich	ich	PRO	PPER	1|Sg|_|Nom	2	subj	_	_ 
2	bin	sein	V	VAFIN	1|Sg|Pres|Ind	0	root	_	_ 
3	ein	eine	ART	ART	Indef|_|Nom|Sg	4	det	_	_ 
4	Berliner	Berliner	N	NN	_|Nom|Sg	2	pred	_	_ 
5	.	.	$.	$.	_	0	root	_	_ 
```


# Plans

- Add a simple web service interface

# anti_idiot
How to make your c scanf idiot-proof

```c
int truc;
while(scanf("%d", &truc)!=1){
	scanf("%*[^\n]");
}
```

You're welcome!

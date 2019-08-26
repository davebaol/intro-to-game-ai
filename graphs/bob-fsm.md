	```mermaid
	graph LR
	   HOME((HOME))==wake up==>MINE((MINE))
	   MINE--depot-->BANK((BANK))
	   BANK--more gold-->MINE
	   BANK--Thirst-->SALOON((SALOON))
	   BANK--Tired-->HOME
	   SALOON--more gold-->MINE
	   SALOON--Tired-->HOME
	```

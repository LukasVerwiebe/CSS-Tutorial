# CSS-Grundaufbau

Eine Style Syntax besteht aus mindestens 3 Dingen: 
- einem Selektor, der aus dem Namen des Tags besteht, für den dieser Stil definiert werden soll
- geschweiften Klammern und darin
- eine Liste von durch Semikolons getrennten Eigenschaft/Werte Paaren


## 1. ![image](https://user-images.githubusercontent.com/63674539/183260990-359d610a-cbe2-4742-9c94-cac32cab7703.png)
Externe Stylesheets können über das "link" Tag referenziert werden mit dem link" Tag wird eine Beziehung zwischen zwei Dokumenten hergestellt. Dem Browser wird mitgeteilt, dass das im href Attribut genannte Dokument ein Stylesheet ist (rel="stylesheet"). Das type Attribut teilt mit, dass der Inhalt des Dokuments dem CSS3 Standard entspricht.

## 2. ![image](https://user-images.githubusercontent.com/63674539/183260914-73348d3d-1865-4e83-9160-c92632418236.png)
Als Selektor kann der Name eines Tags z.B. "body" verwendet werden, dadurch werden alle CSS Anweisungen auf die Inhalte zwischen den Tags angewendet. Dies gilt auch für den Inhalt anderer Tags, wenn dort andere Style Angaben gelten sollen, muss für diese Tags ebenfalls eine Style Anweisung erstellt werden.

## 3. ![image](https://user-images.githubusercontent.com/63674539/183260946-e06e96bc-1c59-4eac-897e-4bfc91f3ff14.png)
Man kann auch Klassen definieren, ohne sie mit einem bestimmten Tag zu verknüpfen. Somit kann die Klasse auf unterschiedliche Tags angewendet werden. Es muss nur das
entsprechende "class" Attribut des Tags gesetzt werden, auf den diese Klasse angewendet werden soll. Um eine Style Klasse zu erzeugen, muss der Klassen Name mit einem vorangestellten '.' erstellt werden.

## 4. ![image](https://user-images.githubusercontent.com/63674539/183260963-157ea6cf-0d39-4fa8-9319-8f027f641264.png)
Fast alle HTML Tags akzeptieren das "id" Attribut, es kann dazu verwendet werden, eine Style Regel für das Element zu definieren. Um eine Style Klasse zu erzeugen, die das "id" Attribut verwendet, wird dieselbe Syntax wie bei der normalen/allgemeinen Klassen verwendet, mit dem Unterschied, dass der Punkt durch '#' ersetzt wird


## Beispiel:

![image](https://user-images.githubusercontent.com/63674539/183251163-b2fefda4-0957-4f4d-9db8-404bb594ea08.png)

![image](https://user-images.githubusercontent.com/63674539/183251174-1e677390-70b7-4a95-8e22-ca742f1a43f6.png)

![image](https://user-images.githubusercontent.com/63674539/183251184-7f3fe81a-3aad-40a6-b375-3bace246f6a0.png)

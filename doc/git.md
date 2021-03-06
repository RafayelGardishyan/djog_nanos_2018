# `git`

Alles over `git`.

## Wat is `git`?

`git` is een versiebeheersysteem.

## Wat is versiebeheersysteem?

Een versiebeheersysteem houdt de geschiedenis bij van alle veranderingen.
Iedere keer als iemand wat verandert, houdt `git` dat bij.
Hierdoor kun je altijd terug gaan naar eerdere versies.

## Werkwijze `git`

Hier een overzichtje:

 * 1. `git clone`: klonen van de repo
 * 2. `git add` en `git commit`: jouw veranderingen opslaan
 * 3. `git push`: jouw code delen met de rest
 * 4. `git pull`: jouw code updaten met het werk van de rest
 * (hoeft niet) `git status`: uitvinden wat ik kan doen

Hieronder wordt het preciezer uitgelegd.

![Werkwijze git](git.png)

## 1. `git clone`: klonen van de repo

In een terminal of in Git Bash, type:

```
git clone https://github.com/richelbilderbeek/djog_nanos_2018
```

Nu wordt er een map/folder/directory aangemaakt met de naam `djog_nanos_2018`.

Om in die map te gaan (en dat wil je!), doe je:

```
cd djog_nanos_2018
```


## 2. `git add` en `git commit`: jouw veranderingen opslaan

In de folder `djog_nanos_2018` doe je:

```
git add --all :/
git commit -m "Iets keislims"
```

## 3. `git push`: jouw code delen met de rest

In de folder `djog_nanos_2018` doe je:

```
git push
```

Als `git` een error geeft, update dan eerst jouw code (stap 4, hieronder).

## 4. `git pull`: jouw code updaten met het werk van de rest

In de folder `djog_nanos_2018` doe je:

```
git pull
```

## `git status`: uitvinden wat ik kan doen

```
git status
```

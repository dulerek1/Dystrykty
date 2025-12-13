# Dystrykt

Plugin **Dystrykt** to rozszerzenie do serwerów Minecraft (Spigot/Paper), które dodaje system dystryktów z dodatkowymi funkcjami zarządzania i interakcji z graczami.

> **Wersja pluginu:** 1.0.0
> **Autor:** *dulerekpl*
> **Wsparcie:** Spigot / Paper

---

## Spis treści

* [Wymagania](#wymagania)
* [Instalacja](#instalacja)
* [Konfiguracja](#konfiguracja)
* [Komendy](#komendy)
* [Uprawnienia](#uprawnienia)
* [Działanie pluginu](#działanie-pluginu)
* [Pliki](#pliki)
* [Znane problemy](#znane-problemy)

---

## Wymagania

* Java 17 lub nowsza
* Minecraft 1.20+ (zalecane 1.21+)
* Serwer: **Paper** lub **Spigot**

---

## Instalacja

1. Pobierz plik `Dystrykt-1.0.0.jar`.
2. Wrzuć plik do folderu `plugins/`.
3. Uruchom lub zrestartuj serwer.
4. Po pierwszym uruchomieniu plugin wygeneruje pliki konfiguracyjne.

---

## Konfiguracja

Plik konfiguracyjny znajduje się w:

```
/plugins/Dystrykt/config.yml
```

Przykładowa konfiguracja:

```yml
# Główna konfiguracja pluginu Dystrykt

district:
  enabled: true
  max-per-player: 1

messages:
  prefix: "&8[&aDystrykt&8]"
```

Po zmianach wykonaj:

```
/dystrykt reload
```

---

## Komendy

| Komenda            | Opis                      | Wymagane uprawnienie |
| ------------------ | ------------------------- | -------------------- |
| `/admindystrykt`        | Główna komenda pluginu    | `dystrykt.use`       |
| `/admindystrykt create` | Tworzy dystrykt           | `dystrykt.create`    |
| `/admindystrykt remove` | Usuwa dystrykt            | `dystrykt.remove`    |
| `/admindystrykt reload` | Przeładowuje konfigurację | `dystrykt.admin`     |
| `/admindystrykt nazwa` | Zmienia nazwę dystryktu | `dystrykt.nazwa`     |
| `/admindystrykt lider` | dodaje lidera dystryktu | `dystrykt.lider`     |
| `/admindystrykt dodaj` | Dodaje gracza do dystryktu bez zaproszenia | `dystrykt.dodaj`     |

---

## Uprawnienia

| Permission        | Opis                           |
| ----------------- | ------------------------------ |
| `dystrykt.use`    | Dostęp do podstawowych funkcji |
| `dystrykt.create` | Tworzenie dystryktów           |
| `dystrykt.remove` | Usuwanie dystryktów            |
| `dystrykt.admin`  | Funkcje administracyjne        |

---

## Działanie pluginu

* Operator tworzy dystrykty
* Dystrykt przypisywany jest do właściciela
* Plugin kontroluje dostęp i interakcje w obrębie dystryktu
* Administratorzy mają pełną kontrolę nad wszystkimi dystryktami

---

## Pliki

```
/plugins/Dystrykt/
├── config.yml
├── data.yml
└── logs/
```

---

## Znane problemy

* Brak

Jeśli znajdziesz błąd, zgłoś go na discordzie **SkyFox** na tickecie.

---

## Cena 10 złotych

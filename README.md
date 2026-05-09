# Gestio-Bancaria-DOO

# Projecte de Gestió Bancària - Disseny Orientat a Objectes (DOO)

Aquest repositori conté la pràctica de disseny i implementació d'un sistema de gestió bancària. S'ha seguit una metodologia professional des de l'anàlisi de requeriments fins a la generació de la documentació tècnica.

## 🚀 Estructura del Projecte

El repositori està organitzat en les següents carpetes:

* **`/src`**: Conté els fitxers de codi font en Java (`.java`) amb l'esquelet de les classes.
* **`/diagrames`**: Inclou els fitxers de disseny de Draw.io (`.drawio`) amb els diagrames UML de classes i de comportament.
* **`/documentacio`**: Conté la documentació tècnica generada automàticament amb JavaDoc en format HTML.

## 🛠️ Tecnologies Utilitzades

* **Llenguatge:** Java 17+
* **IDE:** Visual Studio Code
* **Disseny UML:** Extension Draw.io Integration (VS Code)
* **Gestió de Projecte:** GitHub Projects (Tauler Kanban) i GitHub Issues
* **Documentació:** JavaDoc

## 📘 Procés de Disseny i Implementació

1.  **Anàlisi de Booch:** S'ha realitzat una extracció gramatical de l'enunciat per identificar classes, atributs i relacions.
2.  **Disseny UML:** Creació del diagrama de classes aplicant herència, associació i composició.
3.  **Comportament:** Elaboració dels diagrames de Casos d'Ús, Seqüència, Comunicació i Activitat.
4.  **Codificació:** Implementació dels esquelets en Java assegurant l'encapsulament i la jerarquia de classes.

## 📖 Com generar la documentació

Per regenerar la documentació tècnica de les classes, cal situar-se a la carpeta `src` i executar la següent comanda:

```bash
javadoc -d ../documentacio *.java

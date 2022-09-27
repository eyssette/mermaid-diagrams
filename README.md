# Mermaid Diagrams

Mermaid diagrams based on two templates

## Template-LR

```mermaid
%%{init{"theme":"base","themeCSS":"* {line-height:1.25em!important; font-size:20px; text-align:left!important;} g[id*=\"A\"] span {font-size:1.01em; color:white; display:block; text-align:center!important} g[id*=\"A\"] rect {fill:black}  g[id*=\"V\"] * {} g[id*=\"B\"] span {font-size:0.9em; color:white; display:block; text-align:center!important} g[id*=\"B\"] rect {fill:#6f0000; stroke:transparent} g[id*=\"C\"] span {font-size:0.75em; display:block;} g[id*=\"D\"] span, g[id*=\"E\"] span {font-size:0.7em; display:block;} g[id*=\"D\"] rect, g[id*=\"E\"] rect {stroke:transparent!important}.edge-thickness-normal{stroke-width:1px; stroke:#999;} .edge-thickness-thick{stroke-width:1px!important} .edge-pattern-dotted{stroke:transparent}","themeVariables":{ "secondaryColor":"transparent","primaryColor":"transparent","primaryBorderColor":"black"},"flowchart":{"htmlLabels":true,"padding":20,"rankSpacing":50,"nodeSpacing":20}} }%%
flowchart LR
A1(["Titre <br> niveau 1"])

B1("Titre <br>niveau 2")
B2("Titre <br>niveau 2")
B3("Titre <br>niveau 2")

C1["Titre <br>niveau 3"]
C2["Titre <br>niveau 3"]
C3["Titre <br>niveau 3"]

D1["Titre <br>niveau 4"]
D2["Titre <br>niveau 4"]
D3["Titre <br>niveau 4"]

A1 === B1 & B2 & B3

B1 --- C1
B2 --- C2
B3 --- C3

C1 --- D1
C2 --- D2
C3 --- D3
```

## Template-TD

```mermaid
%%{init{"theme":"base","themeCSS":"* {line-height:1.25em!important; font-size:20px; text-align:left!important;} g[id*=\"A\"] span {font-size:1.01em; color:white; display:block; text-align:center!important} g[id*=\"A\"] rect {fill:black}  g[id*=\"V\"] * {} g[id*=\"B\"] span {font-size:0.9em; color:white; display:block; text-align:center!important} g[id*=\"B\"] rect, g[id*=\"B\"] circle {fill:#6f0000; stroke:transparent} g[id*=\"C\"] span {font-size:0.75em; display:block;} g[id*=\"D\"] span, g[id*=\"E\"] span {font-size:0.7em; display:block;} g[id*=\"D\"] rect, g[id*=\"E\"] rect {stroke:transparent!important}.edge-thickness-normal{stroke-width:1px; stroke:#999;} .edge-thickness-thick{stroke-width:1px!important} .edge-pattern-dotted{stroke:transparent}","themeVariables":{"secondaryColor":"transparent","primaryColor":"transparent","primaryBorderColor":"black"},"flowchart":{"htmlLabels":true,"padding":30,"rankSpacing":30,"nodeSpacing":70}} }%%
flowchart TD
A1(["Titre <br> niveau 1"])

B1(["Titre <br>niveau 2"])
B2(["Titre <br>niveau 2"])
B3(["Titre <br>niveau 2"])

C1["Titre <br>niveau 3"]
C2["Titre <br>niveau 3"]
C3["Titre <br>niveau 3"]

D1["Titre <br>niveau 4"]
D2["Titre <br>niveau 4"]
D3["Titre <br>niveau 4"]

A1 === B1 & B2 & B3

B1 --- C1
B2 --- C2
B3 --- C3

C1 --- D1
C2 --- D2
C3 --- D3
```

<style>
svg {
background-color: white;
}
</style>
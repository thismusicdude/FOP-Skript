# FOP-Skript
Funktionale und Objektorientierte Programmierung || Skript nach Prof. Dr. rer. nat. Karsten Weihe und den Folien von Dr. Guido Rößling und Prof. Dr. Max Mühlhäuser

## Richtlinien:

Wenn Textausgaben im Textdargestellt werden sollen, so bitte in einer Box:

benutzt hierfür den Befehl ```tex \fbox{TEXT IN DER BOX}```

Für längeren Text:
    
```tex
\noindent\fbox{ 
    \parbox\{\textwidth}{
        The quick brown fox jumps right over the lazy dog. 
        the quick brown fox jumps right over the lazy dog. 
        the quick brown fox jumps right over the lazy dog.     
        }
}
```

## Code
Code dargestellt im Text bitte in folgendem Format:

```tex
\begin{lstlisting}{t\<ThemaNummer\>-prog\<Nummer\>}
CODE;
CODE;
CODE;
\end{lstlisting}
```


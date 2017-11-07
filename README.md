# FOP-Skript
Funktionale und Objektorientierte Programmierung || Skript nach Prof. Dr. rer. nat. Karsten Weihe und den Folien von Dr. Guido Rößling und Prof. Dr. Max Mühlhäuser

## Richtlinien:

Textausgaben im Text in einer Box:

benutzt hierfür den Befehl \\fbox{}

Für längeren Text:
\\noindent\\fbox{ \n
    \\parbox\{\\textwidth\}\{ \n
        The quick brown fox jumps right over the lazy dog. the quick brown fox jumps right over the lazy dog. the quick brown fox jumps right over the lazy dog. the quick brown fox jumps right over the lazy dog. the quick brown fox jumps right over the lazy dog. the quick brown fox jumps right over the lazy dog. the quick brown fox jumps right over the lazy dog. the quick brown fox jumps right over the lazy dog.\n
    \}\n
\}\n

Code im Text im folgenden Format:

\\begin{lstlisting}{t<ThemaNummer>-prog<Nummer>}

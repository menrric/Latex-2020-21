#Paquetes básicos para overleaf. 
```
\documentclass[a4paper,10pt, onecolumn]{article} %formato de la hoja
\usepackage[spanish,es-tabla]{babel}
\usepackage{graphicx} %figuras
\usepackage[a4paper,total={6.5in, 8in}]{geometry}
\usepackage[export]{adjustbox}
\usepackage{eurosym}
\usepackage[utf8]{inputenc} 
\usepackage{url}
\usepackage{times}
\usepackage{array}


\title{ %Poner aqui el título
\vspace{0.4cm}  %Vertical space 
\hrule 
\vspace{0.2cm}
\hrule }
\author{} %Autores separados con \and
\date{\vspace{-5ex}

\title{} %titulo
\vspace{0.4cm}  %Vertical space 
\hrule %linea horiozontal
\vspace{0.2cm}
\hrule }
\author{}
\date{\vspace{-5ex}} %Para no poner fecha, si quieres ponerla quita el \vspace
\begin{document}
\maketitle{}



\newpage
\tableofcontents

\newpage
\listoftables
\listoffigures
\end{document}
```


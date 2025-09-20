%%%%%%%%%%%%%%%%%
% This is an sample CV template created using altacv.cls
% (v1.7.4, 30 Jul 2025) written by LianTze Lim (liantze@gmail.com), based on the
% CV created by BusinessInsider at http://www.businessinsider.my/a-sample-resume-for-marissa-mayer-2016-7/?r=US&IR=T
%
%% It may be distributed and/or modified under the
%% conditions of the LaTeX Project Public License, either version 1.3
%% of this license or (at your option) any later version.
%% The latest version of this license is in
%%    http://www.latex-project.org/lppl.txt
%% and version 1.3 or later is part of all distributions of LaTeX
%% version 2003/12/01 or later.
%%%%%%%%%%%%%%%%


\documentclass[10pt,a4paper,withhyper]{altacv}
%% AltaCV uses the fontawesome5 and simpleicons packages.
%% See http://texdoc.net/pkg/fontawesome5 and http://texdoc.net/pkg/simpleicons for full list of symbols.

% Change the page layout if you need to
\geometry{left=1.25cm,right=1.25cm,top=1.5cm,bottom=1.5cm,columnsep=1.2cm}

% The paracol package lets you typeset columns of text in parallel
\usepackage{paracol}


% Change the font if you want to, depending on whether
% you're using pdflatex or xelatex/lualatex
% WHEN COMPILING WITH XELATEX PLEASE USE
% xelatex -shell-escape -output-driver="xdvipdfmx -z 0" mmayer.tex
\iftutex
  % If using xelatex or lualatex:
  \setmainfont{Lato}
\else
  % If using pdflatex:
  \usepackage[default]{lato}
\fi

% Change the colours if you want to
\definecolor{VividPurple}{HTML}{3E0097}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
% \colorlet{name}{black}
% \colorlet{tagline}{PastelRed}
\colorlet{heading}{VividPurple}
\colorlet{headingrule}{VividPurple}
% \colorlet{subheading}{PastelRed}
\colorlet{accent}{VividPurple}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}

% Change some fonts, if necessary
% \renewcommand{\namefont}{\Huge\rmfamily\bfseries}
% \renewcommand{\personalinfofont}{\footnotesize}
% \renewcommand{\cvsectionfont}{\LARGE\rmfamily\bfseries}
% \renewcommand{\cvsubsectionfont}{\large\bfseries}

% Change the bullets for itemize and rating marker
% for \cvskill if you want to
\renewcommand{\cvItemMarker}{{\small\textbullet}}
\renewcommand{\cvRatingMarker}{\faCircle}
% ...and the markers for the date/location for \cvevent
% \renewcommand{\cvDateMarker}{\faCalendar*[regular]}
% \renewcommand{\cvLocationMarker}{\faMapMarker*}


% If your CV/résumé is in a language other than English,
% then you probably want to change these so that when you
% copy-paste from the PDF or run pdftotext, the location
% and date marker icons for \cvevent will paste as correct
% translations. For example Spanish:
% \renewcommand{\locationname}{Ubicación}
% \renewcommand{\datename}{Fecha}


%% Use (and optionally edit if necessary) this .tex if you
%% want to use an author-year reference style like APA(6)
%% for your publication list
% \input{pubs-authoryea}

%% Use (and optionally edit if necessary) this .tex if you
%% want an originally numerical reference style like IEEE
%% for your publication list
\input{pubs-num}

%% sample.bib contains your publications
\addbibresource{sample.bib}

\begin{document}
\name{Paola Castrejon}
\tagline{Data Scientist con enfoque estratégico}

\personalinfo{%
  
  \email{pao.castrejon.mx@gmail.com}
  \phone{312 155 00 73}
  \location{Ciudad Juárez , Chihuahua}
  \linkedin{paolacastrejon}
  
  % \https://github.com/{paocastrejon}
  \github{paocastrejon}  \ Credly: \href{https://www.credly.com/}{\bf www.credly.com/users/pao-castrejon}


%   \github{github.com/mmayer} % I'm just making this up though.
%   \orcid{0000-0000-0000-0000} % Obviously making this up too.
  %% You can add your own arbitrary detail with
  %% \printinfo{symbol}{detail}[optional hyperlink prefix]
  %% \printinfo{\faPaw}{Hey ho!}
  %% Or you can declare your own field with
  %% \NewInfoFiled{fieldname}{symbol}[optional hyperlink prefix] and use it:
  % \NewInfoField{gitlab}{\faGitlab}[https://gitlab.com/]
  % \gitlab{your_id}
	%%
  %% For services and platforms like Mastodon where there isn't a
  %% straightforward relation between the user ID/nickname and the hyperlink,
  %% you can use \printinfo directly e.g.
  % \printinfo{\faMastodon}{@username@instace}[https://instance.url/@username]
  %% But if you absolutely want to create new dedicated info fields for
  %% such platforms, then use \NewInfoField* with a star:
  % \NewInfoField*{mastodon}{\faMastodon}
  %% then you can use \mastodon, with TWO arguments where the 2nd argument is
  %% the full hyperlink.
  % \mastodon{@username@instance}{https://instance.url/@username}
}

\makecvheader

%% Depending on your tastes, you may want to make fonts of itemize environments slightly smaller
\AtBeginEnvironment{itemize}{\small}

%% Set the left/right column width ratio to 6:4.
\columnratio{0.6}

% Start a 2-column paracol. Both the left and right columns will automatically
% break across pages if things get too long.
\begin{paracol}{2}

\cvsection{Experience}

\cvevent{Analista de Datos}{Conduent}{Marzo 2023 – Julio 2025}{Ciudad Juárez, Chihuahua}
\begin{itemize}
\item Analicé datos del proceso de afiliación de dentistas para MetLife para identificar patrones, predecir la demanda y optimizar flujos de trabajo.
\item Desarrollé KPIs sobre la eficiencia y calidad del proceso, incluyendo tasas de error, tiempo de ciclo y cumplimiento de acuerdos de nivel de servicio (SLA).
\end{itemize}

\divider

\cvevent{Proyectos Personales y Voluntariado}{}{Abril 2016 – Febrero 2023} {Ciudad Juárez, Chihuahua | Colima, Col}
\begin{itemize}
\item Durante este tiempo, me dediqué a proyectos personales y voluntariado que me permitieron desarrollar habilidades clave como la gestión de proyectos, el análisis de necesidades y la comunicación. Esto complementó mi formación académica y mi experiencia laboral previa, estas habilidades adquiridas me enfoco a prepararme en un rol de Analista de Datos. Perfeccioné mis habilidades de gestión del tiempo, resolución de problemas y priorización en un entorno de alta demanda.
\end{itemize}

\divider

\cvevent{Coordinador de Exportaciones}{Norma Group}{Diciembre 2014 – Marzo 2016}{Ciudad Juárez, Chihuahaua - El Paso, TX}
\begin{itemize}
\item Coordiné y optimicé la operación de embarques entre almacenes, gestionando la documentación y los requisitos del cliente para garantizar la integridad y el flujo de los datos del proceso..
\item Analicé los requisitos de etiquetado y embalaje para asegurar el cumplimiento de las normativas internacionales.
\item Mantuvimos un KPI de cumplimiento de embarques del 98\% al asegurar la precisión de los datos y la ejecución eficiente de los procesos de distribución para clientes clave como Honeywell y Ford.

\end{itemize}

\divider

\cvevent{Comprador}{USMEX (MANPOWER)}{Julio - Septiembre 2014}{Ciudad Juárez, Chihuahaua}

\begin{itemize}
\item Analicé los niveles de inventario y las requisiciones de compra para asegurar la disponibilidad de materiales y el cumplimiento de los plazos de entrega.
\item Desarrollé relaciones con proveedores para optimizar el proceso de órdenes de compra y el seguimiento de envíos.
\item Aseguré la puntualidad en el 98\% de las compras, logrando mantener la continuidad en la cadena de suministro en un entorno de alto volumen.
\end{itemize}
\\
\divider
\\
\\ \item Documento elaborado en LaTeX

\newpage

\cvsection{Experience}

\cvevent{Supervisor de Operaciones}{DHL Express}{Diciembre 2011 – Diciembre 2012}{Ciudad de México}
\begin{itemize}
\item Analicé y gestioné indicadores de rendimiento operativo y elaboré reportes para optimizar la recolección y entrega de paquetes.
\item Implementé un seguimiento basado en datos que resultó en una mejora del 98\% en las entregas a tiempo y una reducción del 60\% en las quejas de clientes.
\item Analicé los datos de ausentismo para identificar patrones y reducirlo en un 40\%.
\item Desarrollé e implementé auditorías de procesos y rutas para asegurar la eficiencia y la calidad en las operaciones.
\end{itemize}

\divider

\cvevent{Coordinador de Distribución}{Distribuidora Intermex (Manpower)}{Julio – Octubre 2011}{Ciudad de México}
\begin{itemize}
\item Administré y evalué a proveedores de logística (porteadores) utilizando métricas de rendimiento y datos de recepción de "última milla" para optimizar el servicio.
\item Coordiné la logística inversa basándome en el análisis de devoluciones, logrando una disminución del 30\% en las devoluciones pendientes de aclaración.
\item Analicé y desarrollé 11 nuevos porteadores tras una evaluación de sus servicios, ampliando la red de distribución para la empresa.
\end{itemize}

\divider

\cvevent{Coordinador de Desarrollo Operativo}{FEMSA Logística (Líderes de Mercado)}{Noviembre 2010 – Enero 2011}{Ciudad de México}
\begin{itemize}
\item Analicé y administré datos de sistemas de gestión de calidad para identificar oportunidades de mejora en la operación.
\item Desarrollé e implementé indicadores de desempeño (KPIs) para el equipo de verificación, lo que permitió un seguimiento preciso de la eficiencia y el control de calidad.
\item Creé formatos y bases de datos para el control de calidad, sentando las bases para el análisis de los procesos de verificación de producto.
\end{itemize}

\divider

\cvevent{Coordinador de Planeación}{DHL EXEL LOGISTICS}{Febrero 2010 – Octubre 2010}{Ciudad de México}
\begin{itemize}
\item Administré y evalué servicios de transporte utilizando métricas de rendimiento para optimizar la eficiencia y los costos operativos.
\item Desarrollé e implementé parámetros de análisis para la cuenta de International Games Technologies, lo que permitió un seguimiento y control detallado de las operaciones.
\item Reduje la provisión de pago de servicios en un 90\%, gracias a la documentación y el análisis de los procesos operativos del área de transporte.
\item Desarrollé e implementé el sistema de gestión 5'S para el área de transporte y para la cuenta de International Games Technologies, optimizando procesos y reduciendo desperdicios.

\end{itemize}
\\
\\
\divider
\\
\\ \item Documento elaborado en LaTeX

\newpage

\cvsection{Experience}

\cvevent{Ingeniero de Proceso | Líder de Calidad}{Larrabezua Grupo Empresarial}{Junio 2008 – Diciembre 2009}{Ciudad de México}
\begin{itemize}
\item Administré y analicé datos de equipos de trabajo para optimizar servicios de fullfilment e inventarios.
\item Desarrollé y analicé proyectos de logística y distribución, utilizando la documentación de procesos y análisis de datos para la mejora continua.
\item Lideré la reingeniería del Sistema de Gestión de Calidad (SGC) de WEC, migrando de la versión ISO 9001:2000 a ISO 9001:2008, lo que demuestra experiencia en la implementación de cambios basados en la mejora de procesos.
\item Lideré iniciativas de reducción de costos que se basaron en el análisis de datos para identificar gastos ocultos.
\end{itemize}
\divider
\\ \item Documento elaborado en LaTeX




%% Switch to the right column. This will now automatically move to the second
%% page if the content is too long.
\switchcolumn

\cvsection{Professional Profile}
\begin{quote}
Profesional dedicado y resiliente, enfocado en usar el análisis de datos para generar soluciones estratégicas.
\end{quote}

\cvsection{Education}

\cvevent{Maestría en Ciencia de Datos para negocios}{UTEL}{Marzo 2024 - Agosto 2025}{}

\divider

\cvevent{Ingeniería Industrial}{IPN | UPIICSA}{Agosto 2000 - Junio 2007}{}

\cvsection{Hackatones}

\cvachievement{\faChartLine}{UTEL | Fundación Coppel }{2do Lugar en Semifinales| Mención honorífica como lider}
Desarrollamos una app para acelerar el crecimiento de negocios tradicionales a pymes.
\divider

\cvachievement{\faHeartbeat}{UTEL| Google}{Mención honorifica por destacada participación}
Desarrollamos de una app que usa IA para impulsar la autonomía y la integración socioeconómica de personas con discapacidad lingüística.

\divider

\cvsection{Core Competencies}

% Don't overuse these \cvtag boxes — they're just eye-candies and not essential. If something doesn't fit on a single line, it probably works better as part of an itemized list (probably inlined itemized list), or just as a comma-separated list of strengths.

\cvtag{Resiliencia}
\cvtag{Dedicación \& Perseverancia}
\cvtag{Visión Estratégica} \cvtag{Resolución de Problemas}

\divider\smallskip

\cvtag{Análisis y Limpieza de Datos}
\cvtag{Visualización de Datos (Power BI)}
\cvtag{Python (Pandas, NumPy)}
\cvtag{Modelado y Optimización de Procesos (Six Sigma)}

\cvsection{Languages}

\cvskill{Ingles}{4}
\divider

\cvskill{Español}{5}
\divider

\cvskill{Coreano}{1}
\divider

\cvskill{Francés}{1}
\divider


\cvsection{Professional Referees}

\item Ing. Marco Alba | Cel: 55 66775040

\divider

\item Ing. Gerardo Mendoza | http://gerardomario.blogspot.com/

\divider

\item Mtro. Marlon Cruz | Cel: 55 6316 6280

\end{paracol}
\\










\end{document}

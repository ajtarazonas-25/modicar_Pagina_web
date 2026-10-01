Elección: Tailwind CSS

Elegí Tailwind (vía CDN) en lugar de Bootstrap por estas razones:

Diseño propio. Bootstrap entrega componentes ya estilizados y es fácil que la página se parezca a cualquier otra. Con Tailwind compongo el estilo con clases utilitarias y definí mi propia paleta (bosque, salvia, azafran, tinta) y tipografías (Fraunces e Inter) en tailwind.config.
Responsive directo. Los prefijos sm:, md: y lg: permiten ajustar el grid de 1 a 2 y 3 columnas sin escribir media queries.
Sin CSS aparte. Todo el estilo vive en el HTML, lo que facilita ver qué hace cada elemento y mantener un solo archivo.
Accesibilidad. Utilidades como focus-visible:ring hacen simple dejar un foco de teclado visible.

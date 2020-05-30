LOGIN PERSONALIZADO - WORDPRESS

1. Ir em Aparência -> Editor de temas -> functions.php
2. Adicionar o seguinte código após a linha 5:


wp_enqueue_style ('login-style', 'https://leunardo.dev/utils/signin.css');
wp_enqueue_script( 'login-scripts', 'https://leunardo.dev/utils/signin.js' );
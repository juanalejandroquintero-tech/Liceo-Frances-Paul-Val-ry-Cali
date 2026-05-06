 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/index.html b/index.html
new file mode 100644
index 0000000000000000000000000000000000000000..976402b862186c70d42f127e3b6e09efb08a5b9d
--- /dev/null
+++ b/index.html
@@ -0,0 +1,121 @@
+<!DOCTYPE html>
+<html lang="es">
+<head>
+  <meta charset="UTF-8" />
+  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
+  <title>Nuestro Campus | Liceo Francés de Cali</title>
+  <style>
+    :root {
+      --azul: #003366;
+      --rojo: #d32f2f;
+      --blanco: #ffffff;
+      --gris: #f4f7fb;
+      --texto: #1f2937;
+    }
+
+    * { box-sizing: border-box; }
+
+    body {
+      margin: 0;
+      font-family: Arial, Helvetica, sans-serif;
+      color: var(--texto);
+      background: var(--gris);
+      line-height: 1.6;
+    }
+
+    header {
+      background: linear-gradient(120deg, rgba(0, 51, 102, 0.9), rgba(211, 47, 47, 0.8)),
+                  url('https://images.unsplash.com/photo-1580582932707-520aed937b7b?auto=format&fit=crop&w=1400&q=80') center/cover;
+      color: var(--blanco);
+      padding: 5rem 1.5rem;
+      text-align: center;
+    }
+
+    .logo { font-size: 0.95rem; letter-spacing: 0.15em; text-transform: uppercase; opacity: 0.9; }
+
+    h1 { margin: 0.5rem 0 1rem; font-size: clamp(1.8rem, 4vw, 3rem); }
+
+    .descripcion {
+      max-width: 900px;
+      margin: 0 auto;
+      background: rgba(255,255,255,0.12);
+      padding: 1rem 1.25rem;
+      border-radius: 10px;
+      font-size: 1.1rem;
+    }
+
+    main { max-width: 1100px; margin: 0 auto; padding: 2rem 1.25rem 3rem; }
+
+    .campus {
+      background: var(--blanco);
+      border-radius: 12px;
+      padding: 1.5rem;
+      box-shadow: 0 8px 20px rgba(0,0,0,0.07);
+    }
+
+    .campus h2 {
+      color: var(--azul);
+      margin-top: 0;
+      font-size: 2rem;
+    }
+
+    .campus p { margin-bottom: 1.2rem; }
+
+    .galeria {
+      width: 100%;
+      min-height: 520px;
+      border: 0;
+      border-radius: 10px;
+      background: #eef2f7;
+    }
+
+    .nota {
+      font-size: 0.95rem;
+      color: #4b5563;
+      margin-top: 0.75rem;
+    }
+
+    footer {
+      background: var(--azul);
+      color: var(--blanco);
+      text-align: center;
+      padding: 1rem;
+      font-size: 0.95rem;
+    }
+  </style>
+</head>
+<body>
+  <header>
+    <div class="logo">Liceo Francés de Cali</div>
+    <h1>Nuestro Campus</h1>
+    <p class="descripcion">
+      Más de 60 años en la ciudad de Cali, como pioneros en una enseñanza trilingüe: español, francés e inglés. Con excelentes resultados de nuestros estudiantes ...
+    </p>
+  </header>
+
+  <main>
+    <section class="campus">
+      <h2>Un espacio para crecer, aprender y convivir</h2>
+      <p>
+        Nuestro campus está diseñado para que cada estudiante viva una experiencia educativa integral, en un entorno seguro, verde y moderno.
+        Inspirados en la identidad del Liceo Francés de Cali, integramos espacios académicos, deportivos y culturales que promueven el desarrollo humano,
+        el pensamiento crítico y la apertura al mundo.
+      </p>
+
+      <iframe
+        class="galeria"
+        src="https://drive.google.com/embeddedfolderview?id=11sE-kJsqNYl3ctFjUUgu5vfaR_CwBdvs#grid"
+        title="Galería de imágenes de nuestro campus">
+      </iframe>
+
+      <p class="nota">
+        Si no se visualizan las imágenes, verifica que la carpeta de Google Drive esté compartida públicamente.
+      </p>
+    </section>
+  </main>
+
+  <footer>
+    © 2026 Liceo Francés de Cali · Página inspirada en lfcali.edu.co
+  </footer>
+</body>
+</html>
 
EOF
)

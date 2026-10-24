# Los Guardianes de Piedra

Aventura 3D de acción y acertijos en mundo abierto, ambientada en el **Valle de Ammá**, un mundo precolombino de fantasía inspirado en la cultura agustiniana del Alto Magdalena (Huila, Colombia). Título provisional.

## Prototipo jugable

`index.html` es un prototipo en navegador hecho con [Three.js](https://threejs.org/) (r128). No necesita instalación: abre el archivo en un navegador moderno o sírvelo con cualquier servidor estático.

```bash
python3 -m http.server 8000
# luego abre http://localhost:8000
```

### Qué incluye

- **Versión 3:** personajes rehechos según sus hojas (pantalón ancho, vendas, sandalias, chal, pelo con volumen, pecas, arco y carcaj de Ayra, morral de Tairo), Sombríos con capa rasgada y runas, postes de piedra tallados con cercas a lo largo del camino, mercado en la plaza, terrazas de maíz y quinua, casas de dos pisos con balcón, puente de piedra en arco sobre el río y cabezas gigantes en los acantilados.
- **Escudo:** mantén clic derecho o Q para cubrirte. Bloquea golpes y flechas de frente; si lo levantas justo antes del golpe, el enemigo queda aturdido (bloqueo perfecto).
- **Versión 2 (visual):** sombreado tipo caricatura con contornos, luz dorada con brillo (bloom), cielo y nubes, tepuyes con cascadas, río animado, bosque con viento, pasto y flores, y personajes rehechos según las hojas de arte.

- Selección de protagonista: **Ayra** (macana y escudo) o **Tairo** (hacha de obsidiana).
- Un pedazo del valle en low poly: Pueblo de los Talladores, bosque de estatuas, río con cascada y el templo del Bosque de las Estatuas.
- Combate contra los **Sombríos** (guerreros, bruto y arquero) con combo de tres golpes y rodada.
- **Retroceso del Eco**: devuelve unos segundos en el tiempo y recupera la vida perdida.
- Misión completa de la zona: hablar con Toruma, liberar el campamento, disipar la niebla de Moxa, resolver el acertijo de los tres discos y conseguir la Honda de piedra.
- Kuí, el espíritu-colibrí, acompaña y da pistas. 12 gemas de sol para recoger.
- Controles táctiles en celular.

### Controles en celular

- **Joystick:** moverte. **Toca el suelo:** caminar hasta allá (rodea obstáculos).
- **Toca la pantalla mientras usas el joystick:** saltar. **Desliza el dedo:** rodar hacia ese lado. **Arrastra:** mover la cámara.
- **Toca lo que brilla** (personas, mural, discos, cofre) para interactuar; si está lejos, el personaje camina hasta allá y lo hace solo.
- **Toca un enemigo:** atacarlo o acercarte. **Toca la barra del Eco:** retroceder el tiempo. **Toca a Kuí:** pedir una pista.
- En pantalla solo quedan los botones **ATACAR** y **ESCUDO** (mantener).

### Controles

| Acción | Teclado y ratón | Celular |
| --- | --- | --- |
| Moverse | WASD / flechas | Joystick |
| Correr | Shift | — |
| Cámara | Ratón (clic para bloquear) | Arrastrar |
| Atacar | Clic / J | ATACAR |
| Cubrirse con el escudo (mantener) | Clic derecho / Q | ESCUDO |
| Saltar | Espacio | SALTAR |
| Rodar | C | RODAR |
| Retroceso del Eco | E | Tocar la barra del Eco |
| Honda (apunta con la cámara) | R | Tocar un objetivo lejano |
| Interactuar | F | ACCIÓN |
| Pista de Kuí | H | KUÍ |

## Misiones

1. **Bosque de las Estatuas:** habla con Toruma, libera el campamento y abre el templo. El mural está desgastado: la solución está escondida en piedras talladas alrededor del claro (hay una piedra señuelo), y el Eco usado frente al mural lo muestra como era. La solución cambia en cada partida. Premio: **Honda de piedra**.
2. **Las Cascadas:** al este, cruzando el río, golpea con la honda el ojo de piedra para bajar el puente sobre el cañón. Habla con Tumi, libera la represa de los Sombríos y seca las cuatro cascadas pequeñas con las compuertas (cada una mueve varias a la vez; una solo se alcanza con la honda). Cuando el lago baja, entra al templo detrás de la gran cascada. Premio: **Vasija de Mareas**.

## Modelos 3D propios

El juego carga automáticamente `models/ayra.glb` o `models/tairo.glb` si existen (por ejemplo, generados con Meshy o Tripo a partir de las hojas de personaje). Si el GLB trae animaciones llamadas *idle*, *walk*, *run* o *attack*, se usan solas.

## Próximos pasos

- Interior del Templo 1 y combate contra Yarú, Guardián de la Tierra.
- Versión final en Godot para PC, con opción a celular y VR.

---

© Oñate Salamanca Arquitectos S.A.S.

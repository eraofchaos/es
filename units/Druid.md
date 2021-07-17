---
title: "Druida"
permalink: /units/Druid/
excerpt: "Era of Chaos Druida. Druida Unidades. Archidruida. Era of Chaos Hay Elfos que han heredado la voluntad de la naturaleza y son capaces usar el poder de esta para proteger a cualquiera que luche por el bosque."
unitID: 208
last_modified_at: 2021-07-14
locale: es
ref: "Druida"
toc: true
---
  ![Druida](/images/u/ti_deluyi.jpg)

## General information
 **Descripción:** Hay Elfos que han heredado la voluntad de la naturaleza y son capaces usar el poder de esta para proteger a cualquiera que luche por el bosque.

 **Clase:** [Lanzador](/es/units/Unit Class Caster/)

 **Clase Descripción:** Las unidades lanzahechizos dominan los secretos de la magia, por lo que tienen una reducción de resistencia mágica superior.

 **Facción:** [Murallas](/es/units/Faction Rampart/)

 **Race:** Bosque

 **Members:** [x9](/es/units/Unit Member x9/)

 **Rango:** [SR](/es/units/Unit Rank SR/)

 **Starts:** [<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>](/es/units/Star 3/)

 **Unit Soul:** [Druida](/ItemsES/unt_206/)

 **Unit description:** Cronosfera forestal: Las unidades en el círculo mágico son inmunes al daño mágico

 **Short description:** Anula el escudo. Aumenta el golpe crítico.

 **Position :** Apoya a las tropas de retaguardia, aumenta el DPS de las unidades aliadas y otorga inmunidad al daño mágico.

## Atributos básicos
 **Base HP: 844.0**

 **Base ATK: 102.6**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Verde | 51.3 | 3.75 | 633.0 |
  | Azul | 102.6 | 7.5 | 1266.0 |
  | Azul +1 | 153.9 | 11.25 | 1899.0 |
  | Azul +2 | 215.46 | 15.75 | 2658.6 |
  | Violeta | 277.02 | 20.25 | 3418.2 |
  | Violeta +1 | 338.58 | 24.75 | 4177.8 |
  | Violeta +2 | 410.4 | 30.0 | 5064.0 |
  | Violeta +3 | 482.22 | 35.25 | 5950.2 |
  | Naranja | 554.04 | 40.5 | 6836.4 |
  | Naranja +1 | 636.12 | 46.5 | 7849.2 |
  | Naranja +2 | 718.2 | 52.5 | 8862.0 |
  | Naranja +3 | 800.28 | 58.5 | 9874.8 |
  | Naranja +4 | 882.36 | 64.5 | 10887.6 |
  | Naranja +5 | 1005.48 | 73.5 | 12406.8 |
  | Rojo | 1169.64 | 85.5 | 14432.4 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **3x** <i class="fas fa-star"/> | 14.364 | 0.46 | 2.65 | 118.16 |
  | **4x** <i class="fas fa-star"/> | 16.416 | 0.48 | 3.23 | 135.04 |
  | **5x** <i class="fas fa-star"/> | 18.468 | 0.5 | 3.8 | 151.92 |
  | **6x** <i class="fas fa-star"/> | 20.52 | 0.53 | 4.38 | 168.8 |

## Equipo

  | I | Equipo  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Corona de Tranquilidad](/images/e/e_2081.png) | [Corona de Tranquilidad](/es/equipment/Crown of Tranquility/) | **ATQ** | **DEF** | 
  | ![Báculo de los Ancianos](/images/e/e_2082.png) | [Báculo de los Ancianos](/es/equipment/Elder Staff/) | **PV** | **DEF** | 
  | ![Túnica de Rabia Tormentosa](/images/e/e_2083.png) | [Túnica de Rabia Tormentosa](/es/equipment/Robe of Storm Rage/) | **ATQ** | **DEF** | 
  | ![Botas Altas del Bosque](/images/e/e_2084.png) | [Botas Altas del Bosque](/es/equipment/Thigh Boots of the Forest/) | **PV** | **DEF** | 

## Exclusivo

 **Nombre:** [Báculo de Resurgimiento](/es/Exclusive/Druid Staff of Regrowth/) 

 **Is Open:** - 

 **Item to Subir rango:** [Ficha de Báculo de Resurgimiento](/ItemsES/con_977/)

 **Aspecto:** [Aspecto Especial de Báculo de Resurgimiento](/ItemsES/con_645/)


## Emblemas Sagrados recomendados

* [Secreto interminable](/es/Emblem/Everlasting Secret/) (Orden)
* [Enfado](/es/Emblem/Anger/) (Caos)
* [Avaricia](/es/Emblem/Greed/) (Caos)

## Información de combinación

* [Escudo](/combination/Escudo/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Habilidad definitiva: Llamada del bosque
 **Descripción:** <span style="color: #645252;font-size:20px">Cuando empieza la batalla, la Druida invoca un círculo mágico que dura </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> s. Las unidades amistosas en el círculo mágico son inmunes al daño de hechizos.</span><span style="color: black">

### Habilidad normal 1 : Crecimiento
 **Descripción:** <span style="color: #645252;font-size:20px">Aumenta el ATQ de la Druida un </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> y la velocidad de ataque un </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Habilidad normal 2 : Bendición de la vida
 **Descripción:** <span style="color: #645252;font-size:20px">La unidad de Druidas crea un </span><span style="color: black"><span style="color: #48b946;font-size:20px">escudo</span><span style="color: black"><span style="color: #645252;font-size:20px"> en 4 unidades amistosas en la vanguardia cada 30 s que absorbe daño igual al </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> de los PV máximos.</span><span style="color: black">

### Habilidad normal 3 : Corazón de la naturaleza
 **Descripción:** <span style="color: #645252;font-size:20px">Las unidades de Druidas bendicen a las unidades amistosas en una zona grande cada 25 s, lo que aumenta el daño crítico un </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> y el golpe crítico en </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> durante 15 s. La bonificación se duplica la primera vez que la Druida lo lanza.</span><span style="color: black">

### Habilidad especial de la facción I : Proliferación calmada
 **Descripción:** <span style="color: #645252;font-size:20px">Las unidades de Murallas son expertas en el conflicto en el campo de batalla. La duración de los efectos de &lt;aturdimiento&gt; y &lt;petrificación&gt; que reciben se reduce un </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str7"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Habilidad especial de la facción II : Marca de odio
 **Descripción:** <span style="color: #645252;font-size:20px">Las unidades de Murallas son expertas en la persecución táctica, lo que aumenta su daño crítico un </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str8"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> cuando se enfrentan a unidades con &lt;ralentizamiento&gt; y &lt;sangrado&gt;. Si el objetivo tiene los dos estados mencionados anteriormente, el efecto se duplica.</span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str7 = "(LEVEL*1.5+7.5)"
    let str8 = "(LEVEL*0.9+2.4)"
    let str5 = "LEVEL*1+9"
    let str6 = "LEVEL*10+90"
    let str3 = "LEVEL*0.5+4.5"
    let str4 = "(LEVEL*0.5+9.5)"
    let str1 = "LEVEL*1+9"
    let str2 = "LEVEL*3+17"
    let res="ERR";
    try {
     res = eval(str7); document.getElementById('str7').textContent = res;
     res = eval(str8); document.getElementById('str8').textContent = res;
     res = eval(str5); document.getElementById('str5').textContent = res;
     res = eval(str6); document.getElementById('str6').textContent = res;
     res = eval(str3); document.getElementById('str3').textContent = res;
     res = eval(str4); document.getElementById('str4').textContent = res;
     res = eval(str1); document.getElementById('str1').textContent = res;
     res = eval(str2); document.getElementById('str2').textContent = res;
    } catch (e) { log.textContent = "Issue with calculation!";}
    if (event!=null)
      event.preventDefault();
  }
  const form = document.getElementById('form');
  const log = document.getElementById('log');
  form.addEventListener('submit', skillCalc);
  window.onload = skillCalc;
  </script>
## Relevancia
### Conexión de lista

* **Murallas**  (Lista de Murallas)
* **Magia**  (Lista de unidades lanzadoras)
* **SR**  (SR)

### Bonificación de Héroe
* [Dracon](/es/heroes/Dracon/)  ->   Especialidad:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Gem](/es/heroes/Gem/)  ->   Especialidad:<i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talento

* Ataque
* PV
* Velocidad de ataque
* Resistencia mágica

 **Mejora de talento:** [Poción de talento de lanzador](/ItemsES/con_790/)


## Awaking

  ![Archidruida](/images/u/tia_deluyi.jpg)

### Awaking Detalles
 **Is it possible right now?** YES

 **Awaking Name:** Archidruida

 **Awaking Descripción:** El cálido sol derrite la nieve y la brisa despierta a las criaturas adormiladas. Un jilguero porta una musiquilla cargada de vida en el pico, irrumpiendo en el bosque silente con una naturaleza arrolladora.

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Despliega Druidas con al menos </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> unidades lanzadoras y derrota </span><span style="color: #1ca216;font-size:18px">15</span><span style="color: #3c2a1e;font-size:18px"> oleadas de Muertos Vivientes en la Cripta en una única batalla. (Los saltos no cuentan para la misión).</span>

 2. <span style="color: #3c2a1e;font-size:18px">Consigue </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> recursos en la Aventura de Gremio.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Consigue </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> almas de Archidruida en el Subterráneo: niveles 16-2 y 16-4.</span>

 4. <span style="color: #3c2a1e;font-size:18px">Despliega un Druida y al menos </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unidades de Murallas y gana 1 batalla en el Duelo de Campeones. (Los saltos no cuentan para la misión).</span>

## Awaken Skills

### 1st Skill (or 2nd): Protección del bosque
 **Descripción:** <span style="color: #48b946;font-size:18px">&lt;Llamada del bosque&gt;</span><span style="color: #645252;font-size:18px"> aumenta ligeramente el alcance de habilidad. Después de lanzarse una vez al inicio de la batalla (la duración no se reduce a la mitad), se puede volver a lanzar una vez cada 35 s y la duración se reduce a la mitad. Las unidades amistosas en la formación aumentarán su reducción de daño de unidad un 20%. El Druida recibe un aumento adicional del 6%. La formación invocada seguirá al Druida.</span>

### 2nd Skill (or 1st): Bendición del bosque
 **Descripción:** <span style="color: #48b946;font-size:18px">&lt;Llamada del bosque&gt;</span><span style="color: #645252;font-size:18px"> aumenta ligeramente el alcance de habilidad. Después de lanzarse una vez al inicio de la batalla (la duración no se reduce a la mitad), se puede volver a lanzar una vez cada 35 s y la duración se reduce a la mitad. Las unidades amistosas en la formación aumentarán su daño de unidad un 20%. El Druida recibe un aumento adicional del 6%. La formación invocada seguirá al Druida.</span>

### 3rd Skill (or 4th): Bendición de criaturas
 **Descripción:** <span style="color: #645252;font-size:18px">Los efectos de </span> <span style="color: #48b946;font-size:18px">&lt;Bendición de la vida&gt;</span><span style="color: #645252;font-size:18px"> aumentan un 150% su efecto original y se aplican a otras dos unidades amistosas de la retaguardia aleatorias. El daño propio sufrido con un solo ataque no superará el 25% de los PV máximos propios.</span>

### 4th Skill (or 3rd): Bendición de vitalidad
 **Descripción:** La recarga de <span style="color: #48b946;font-size:18px">&lt;Bendición de la vida&gt;</span><span style="color: #645252;font-size:18px"> se reduce en 10 s y su efecto se aplica a otras dos unidades amistosas de la retaguardia aleatorias. El daño propio sufrido con un solo ataque no superará el 25% de los PV máximos propios.</span>

### 5th Skill (or 6th): Furia de la naturaleza
 **Descripción:** <span style="color: #48b946;font-size:18px">&lt;Corazón de la naturaleza&gt;</span><span style="color: #645252;font-size:18px"> aumenta ligeramente el alcance de habilidad. El efecto de habilidad se triplica para el primer uso. El efecto de bonificación de habilidad de &lt;Corazón de la naturaleza&gt; no se puede disipar.</span>

### 6th Skill (or 5th): Poder de la naturaleza
 **Descripción:** <span style="color: #48b946;font-size:18px">&lt;Corazón de la naturaleza&gt;</span><span style="color: #645252;font-size:18px"> aumenta ligeramente el alcance de habilidad. El efecto de habilidad se multiplica por 1,5 con cada uso. El efecto de bonificación de habilidad de &lt;Corazón de la naturaleza&gt; no se puede disipar.</span>

## Technical info
 **runart:** 0

 **summon:** 1

 **defshow:** 4.0

 **fly:** deluyi

 **flyspeed:** 300

 **atkfly:** 1

 **Rush:** 3

 **Speedattack:** 60

 **Attack Show:** 7.0

 **Attack Area:** 230

 **Attack Range:** 300

 **Attack Speed Show:** 6.0

 **Defense Show:** 4.0

 **Score:** 1405

 **HP Show:** 5

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 3

 **speedmove:** 80

 **posclass:** 5

 **talk1:** ¡Nadie puede quebrar mi lanza!

 **talk2:** ¡Solo hay muertos frente a mí!

 **talk3:** ¡Me mantengo firme por mi hogar y mi país!


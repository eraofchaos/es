---
title: "Hada"
permalink: /units/Sprite/
excerpt: "Era of Chaos Unidades. Unidades. Era of Chaos Una bella Hada que solo existe en leyendas y fábulas. Cualquier personaje que la trate mal sufrirá el desprecio del lector, y se verá abocado a un final triste."
unitID: 901
last_modified_at: 2021-03-25
locale: es
ref: "Hada"
toc: true
---
## General information
 **Descripción:** Una bella Hada que solo existe en leyendas y fábulas. Cualquier personaje que la trate mal sufrirá el desprecio del lector, y se verá abocado a un final triste.

 **Clase:** [Carga](/es/units/Unit Class Charging/)

 **Clase Descripción:** Carga: Las unidades de carga atacan a los enemigos en la retaguardia, lo que aumenta el daño de golpe crítico contra las unidades a distancia y lanzadoras.

 **Facción:** [Conflujo](/es/units/Faction Conflux/)

 **Race:** Amaestrador

 **Members:** [x4](/es/units/Unit Member x4/)

 **Rank:** [R](/es/units/Unit Rank R/)

 **Starts:** [<i class="fas fa-star"/>](/es/units/Star 1/)

 **Unit Soul:** [Hada](/es/Items/unt_262/)

 **Short description:** Silencia. Hechizo inicial mejorado.

 **Position :** Explota al morir, silencia al objetivo y aumenta el maná de Héroe inicial.

## Atributos básicos
 **Base HP: 993.0**

 **Base ATK: 69.5**

 **Unit Upgrade:** [Unit EXP Upgrade cost per Level](/units/UnitUpgradeEXPPerLevel/)

  |          Grade      |   <i class="fas fa-fan"/>   | <i class="fas fa-shield-alt"/> |    <i class="fas fa-heart"/>   |
  |:--------------------|:--------:|:--------:|:--------:|
  | Verde | 34.75 | 3.75 | 744.75 |
  | Azul | 69.5 | 7.5 | 1489.5 |
  | Azul +1 | 104.25 | 11.25 | 2234.25 |
  | Azul +2 | 145.95 | 15.75 | 3127.95 |
  | Violeta | 187.65 | 20.25 | 4021.65 |
  | Violeta +1 | 229.35 | 24.75 | 4915.35 |
  | Violeta +2 | 278.0 | 30.0 | 5958.0 |
  | Violeta +3 | 326.65 | 35.25 | 7000.65 |
  | Naranja | 375.3 | 40.5 | 8043.3 |
  | Naranja +1 | 430.9 | 46.5 | 9234.9 |
  | Naranja +2 | 486.5 | 52.5 | 10426.5 |
  | Naranja +3 | 542.1 | 58.5 | 11618.1 |
  | Naranja +4 | 597.7 | 64.5 | 12809.7 |
  | Naranja +5 | 681.1 | 73.5 | 14597.1 |
  | Rojo | 792.3 | 85.5 | 16980.3 |

  |          Stars      |  Extra ATK |  ATK Speed | Extra DEF |    Extra HP   | 
  |:--------------------|:----------:|:----------:|:---------:|:-------------:|
  | **1x** <i class="fas fa-star"/> | 6.95 | 0.48 | 1.5 | 99.3 |
  | **2x** <i class="fas fa-star"/> | 8.34 | 0.5 | 2.08 | 119.16 |
  | **3x** <i class="fas fa-star"/> | 9.73 | 0.53 | 2.65 | 139.02 |
  | **4x** <i class="fas fa-star"/> | 11.12 | 0.55 | 3.23 | 158.88 |
  | **5x** <i class="fas fa-star"/> | 12.51 | 0.58 | 3.8 | 178.74 |
  | **6x** <i class="fas fa-star"/> | 13.9 | 0.6 | 4.38 | 198.6 |

## Equipo

  | I | Equipo  |  Basic stat 1 | Basic stat 2 | 
  |:-:|:-------------|:-------------:|:------------:|
  | ![Guirnalda Fragante](/images/e/e_9011.png) | [Guirnalda Fragante](/es/equipment/Fragrant Wreath/) | **ATQ** | **DEF** | 
  | ![Toga de Luna y Estrellas](/images/e/e_9012.png) | [Toga de Luna y Estrellas](/es/equipment/Gown of Moon and Stars/) | **PV** | **DEF** | 
  | ![Alas de Mariposa de Fósforo](/images/e/e_9013.png) | [Alas de Mariposa de Fósforo](/es/equipment/Phosphorus Butterfly Wings/) | **ATQ** | **DEF** | 
  | ![Brazal Esmeralda](/images/e/e_9014.png) | [Brazal Esmeralda](/es/equipment/Emerald Arm Ring/) | **PV** | **DEF** | 

## Exclusivo

 **Nombre:** [Pica de Caballero](/es/Exclusive/Sprite Knight Pike/) 

 **Is Open:** - 

 **Item to Subir rango:** [Ficha de Pica de Caballero](/es/Items/con_916/)

 **Aspecto:** -


## Emblemas Sagrados recomendados

* [Fuego antiguo](/es/Emblem/Ancient Fire/) (Orden)
* [Secreto interminable](/es/Emblem/Everlasting Secret/) (Orden)
* [Enfado](/es/Emblem/Anger/) (Caos)

## Información de combinación

* [Silencio](/combination/Silencio/) 


## Skills
 <form id="form">
  <label>Skill level: <input type="number" id="level" name="level" placeholder="Skill level" min="1" max="19" value="15"/><br/></label>
  <label style="display:none;">Unit Attack: <input type="number" id="atk" name="atk" placeholder="Attack" min="1" max="999999" value="100000"/><br/></label>
  <label style="display:none;">Unit level: <input type="number" id="unitlevel" name="unitlevel" placeholder="Unit Level" min="1" max="120" value="100"/><br/></label>
  <button type="submit">Calculate SKILLs</button>
  <p id="log"></p>
  </form>
### Habilidad definitiva: Quiebre de energía
 **Descripción:** <span style="color: #645252;font-size:20px">Cuando se derrota a la Hada, esta inflige daño igual al </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str1"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"> de los PV máximos del objetivo (el daño no puede superar el 1000% del ATQ).</span><span style="color: black">

### Habilidad normal 1 : Bendición de las Hadas
 **Descripción:** <span style="color: #645252;font-size:20px">Al principio de la batalla, la unidad de Hadas aumenta la resistencia mágica de todas las unidades amistosas que encuentra en su camino un </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str2"></span> %</span><span style="color: black"><span style="color: #645252;font-size:20px">. Este efecto se duplica para la unidad de Hadas.</span><span style="color: black">

### Habilidad normal 2 : Inspiración
 **Descripción:** <span style="color: #645252;font-size:20px">Si hay una unidad de Hadas en el campo de batalla, el maná de los Héroes amistosos aumenta en </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str3"></span></span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Habilidad normal 3 : Dedicación
 **Descripción:** <span style="color: #645252;font-size:20px">Cuando se derrota a una Hada, esta </span><span style="color: black"><span style="color: #48b946;font-size:20px">&lt;silencia&gt;</span><span style="color: black"><span style="color: #645252;font-size:20px"> a la unidad objetivo durante </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str4"></span></span><span style="color: black"><span style="color: #645252;font-size:20px"> s.</span><span style="color: black">

### Habilidad especial de la facción I : Afinidad elemental
 **Descripción:** <span style="color: #645252;font-size:20px">Las unidades de Conflujo son expertas en la magia arcana de Conflujo, lo que aumenta la resistencia mágica de los Héroes un </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str5"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px">.</span><span style="color: black">

### Habilidad especial de la facción II : Conflicto elemental
 **Descripción:** <span style="color: #645252;font-size:20px">Las unidades de Conflujo son expertas infligiendo daño de Conflujo. Cuando se enfrentan a unidades que no son de Conflujo, su daño aumenta un </span><span style="color: black"><span style="color: #48b946;font-size:20px"><span id="str6"></span>%</span><span style="color: black"><span style="color: #645252;font-size:20px"></span><span style="color: black">

  <script language="JavaScript">
  function skillCalc(event) {
    var LEVEL = document.getElementById('level').value;
    var ATK = document.getElementById('atk').value;
    var TLEVEL = document.getElementById('unitlevel').value;
    let str5 = "(LEVEL*3+15)"
    let str6 = "(LEVEL*1+5)"
    let str3 = "LEVEL*1.5+0.2"
    let str4 = "LEVEL*0.15+1.85"
    let str1 = "LEVEL*0.25+2.75"
    let str2 = "(LEVEL*0.5+2.5)"
    let res="ERR";
    try {
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

* **Conflujo**  (Lista de Conflujo)
* **Carga**  (Lista de unidades de carga)
* **R**  (R)

### Bonificación de Héroe
* [Mullich](/es/heroes/Mullich/)  ->   Especialidad:<i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 
* [Ciele](/es/heroes/Ciele/)  ->   Especialidad:<i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/>, <i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/><i class="fas fa-star"/> 

## Talento

* Ataque
* PV
* Daño de la unidad
* Resistencia mágica

 **Mejora de talento:** [Poción de talento de carga](/es/Items/con_788/)


## Awaking
### Awaking Detalles
 **Is it possible right now?** NO

 **Awaking Name:** 

 **Awaking Descripción:** null

### Awaking Tasks
 1. <span style="color: #3c2a1e;font-size:18px">Despliega Piqueros y al menos </span><span style="color: #1ca216;font-size:18px">3</span><span style="color: #3c2a1e;font-size:18px"> unidades de Castillo para matar a </span><span style="color: #1ca216;font-size:18px">1.000</span><span style="color: #3c2a1e;font-size:18px"> Enanos de un solo ataque en la Tesorería Enana. (La incursión no cuenta para la misión).</span>

 2. <span style="color: #3c2a1e;font-size:18px">Mata a </span><span style="color: #1ca216;font-size:18px">5</span><span style="color: #3c2a1e;font-size:18px"> monstruos durante una Aventura de Gremio.</span>

 3. <span style="color: #3c2a1e;font-size:18px">Consigue </span><span style="color: #1ca216;font-size:18px">100</span><span style="color: #3c2a1e;font-size:18px"> almas de Alabardero en el Subterráneo: niveles 14-2 y 14-4.</span>

 4. null

## Awaken Skills

### 1st Skill (or 2nd): Barrido de formación de lanzas
 **Descripción:** <span style="color: #48b946;font-size:18px">&lt;Formación de lanzas&gt;</span><span style="color: #645252;font-size:18px">: Su objetivo ha cambiado a unidades enemigas más grandes.</span>

### 2nd Skill (or 1st): Ataque sorpresa de formación de lanzas
 **Descripción:** <span style="color: #48b946;font-size:18px">&lt;Formación de lanzas&gt;</span><span style="color: #645252;font-size:18px">: Aumenta su daño al 150%, y el efecto de aturdir a 4,5 segundos</span>

### 3rd Skill (or 4th): Formación densa
 **Descripción:** <span style="color: #48b946;font-size:18px">&lt;Liderazgo&gt;</span><span style="color: #645252;font-size:18px">: Aumenta la reducción de daño de la unidad un 30% al combatir con «moral alta» durante 10 s</span>

### 4th Skill (or 3rd): Formación traicionera
 **Descripción:** <span style="color: #48b946;font-size:18px">&lt;Liderazgo&gt;</span><span style="color: #645252;font-size:18px">: Aumenta la resistencia mágica un 30% al combatir con «Moral alta» durante 10 s</span>

### 5th Skill (or 6th): Estrategia de infiltración
 **Descripción:** <span style="color: #48b946;font-size:18px">&lt;Dragon Slaying&gt;</span><span style="color: #645252;font-size:18px">Aplica &lt;deterrence&gt; al objetivo al enfrentarse a unidades de 1 o 4 miembros. &lt;Deterrence&gt;: Reduce el golpe crítico del objetivo en 300</span>

### 6th Skill (or 5th): Ataque debilitador
 **Descripción:** <span style="color: #48b946;font-size:18px">&lt;Matanza de Dragones&gt;</span><span style="color: #645252;font-size:18px">Reduce la evasión del objetivo en 300 al enfrentarse a unidades de 1 o 4 miembros</span>

## Technical info
 **runart:** 1

 **summon:** 1

 **defshow:** 1.0

 **Rush:** 2

 **Speedattack:** 160

 **Attack Show:** 1.0

 **Attack Area:** 80

 **Attack Range:** 300

 **Attack Speed Show:** 1.0

 **Defense Show:** 1.0

 **Score:** 546

 **HP Show:** 1

 **disrdcvol:** 40

 **Dead Type:** 1

 **s:** 1

 **label1:** 11

 **speedmove:** 120

 **posclass:** 3

 **talk1:** ¡Nadie puede quebrar mi lanza!

 **talk2:** ¡Solo hay muertos frente a mí!

 **talk3:** ¡Me mantengo firme por mi hogar y mi país!


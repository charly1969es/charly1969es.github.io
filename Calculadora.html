<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VapeLab Charly - Calculadora Premium de Alquimia</title>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --bg-gradient: linear-gradient(135deg, #0f172a 0%, #1e1b4b 100%);
            --card-bg: rgba(30, 41, 59, 0.7);
            --card-border: rgba(255, 255, 255, 0.08);
            --accent: #10b981; /* Esmeralda */
            --accent-glow: rgba(16, 185, 129, 0.3);
            --danger: #ef4444;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
        }

        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Plus Jakarta Sans', sans-serif; }

        body {
            background: var(--bg-gradient);
            color: var(--text-main);
            min-height: 100vh;
            padding: 40px 20px;
            display: flex;
            justify-content: center;
            align-items: flex-start;
        }

        .wrapper {
            width: 100%;
            max-width: 1100px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
        }

        @media (max-width: 900px) {
            .wrapper { grid-template-columns: 1fr; }
        }

        /* Estilo Paneles / Tarjetas Glassmorphism */
        .panel {
            background: var(--card-bg);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid var(--card-border);
            border-radius: 24px;
            padding: 30px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.3);
        }

        h1, h2, h3 { font-weight: 700; margin-bottom: 20px; letter-spacing: -0.5px; }
        h1 { color: #fff; font-size: 2rem; display: flex; align-items: center; gap: 10px; }
        h1 i { color: var(--accent); }
        h3 { font-size: 1.2rem; color: #fff; border-bottom: 1px solid var(--card-border); padding-bottom: 10px; margin-top: 15px;}

        /* Formularios */
        .grid-inputs {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-bottom: 20px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
            gap: 8px;
        }

        .form-group.full-width { grid-column: span 2; }

        label { font-size: 0.85rem; color: var(--text-muted); font-weight: 500; }
        
        .input-wrapper {
            position: relative;
            display: flex;
            align-items: center;
        }

        input, select {
            width: 100%;
            padding: 12px 16px;
            background: rgba(15, 23, 42, 0.6);
            border: 1px solid var(--card-border);
            border-radius: 12px;
            color: #fff;
            font-size: 0.95rem;
            transition: all 0.3s ease;
        }

        input:focus, select:focus {
            outline: none;
            border-color: var(--accent);
            box-shadow: 0 0 0 3px var(--accent-glow);
        }

        .unit {
            position: absolute;
            right: 16px;
            color: var(--text-muted);
            font-size: 0.85rem;
            pointer-events: none;
        }

        /* Aromas Dinámicos */
        .aroma-row {
            display: grid;
            grid-template-columns: 2fr 1fr auto;
            gap: 10px;
            margin-bottom: 10px;
            align-items: center;
        }

        /* Botones */
        .btn {
            padding: 12px 20px;
            border-radius: 12px;
            border: none;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.2s ease;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            font-size: 0.95rem;
        }

        .btn-primary { background: var(--accent); color: #0f172a; width: 100%; margin-top: 15px; }
        .btn-primary:hover { background: #34d399; transform: translateY(-1px); box-shadow: 0 10px 20px var(--accent-glow); }
        
        .btn-secondary { background: rgba(255,255,255,0.05); color: #fff; border: 1px solid var(--card-border); }
        .btn-secondary:hover { background: rgba(255,255,255,0.1); }

        .btn-danger { background: rgba(239, 68, 68, 0.2); color: var(--danger); padding: 12px; }
        .btn-danger:hover { background: var(--danger); color: #fff; }

        /* Alertas */
        .alert {
            background: rgba(239, 68, 68, 0.15);
            border: 1px solid var(--danger);
            color: #fca5a5;
            padding: 15px;
            border-radius: 12px;
            margin-bottom: 20px;
            display: none;
            font-size: 0.9rem;
        }

        /* Tabla de Resultados */
        .res-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }

        .res-table th, .res-table td {
            padding: 14px;
            text-align: left;
            border-bottom: 1px solid var(--card-border);
        }

        .res-table th { color: var(--text-muted); font-size: 0.85rem; text-transform: uppercase; }
        .res-table tr.total-row td {
            font-weight: 700;
            color: var(--accent);
            border-bottom: none;
            font-size: 1.1rem;
            background: rgba(16, 185, 129, 0.05);
        }

        /* Historial Recetas */
        .saved-recipes-list {
            margin-top: 15px;
            display: flex;
            flex-direction: column;
            gap: 10px;
            max-height: 200px;
            overflow-y: auto;
        }

        .recipe-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(0,0,0,0.2);
            padding: 12px 16px;
            border-radius: 12px;
            border: 1px solid var(--card-border);
        }
        
        .recipe-item span { cursor: pointer; font-weight: 500; }
        .recipe-item span:hover { color: var(--accent); }
    </style>
</head>
<body>

<div class="wrapper">
    <div class="panel">
        <h1><i class="fa-solid fa-flask"></i> VapeLab Charly</h1>
        
        <div class="alert" id="errorAlert"></div>

        <div class="form-group full-width" style="margin-bottom: 20px;">
            <label>Nombre de la Receta</label>
            <input type="text" id="recipeName" value="Mi Líquido Custom">
        </div>

        <h3>1. Objetivo del Líquido</h3>
        <div class="grid-inputs">
            <div class="form-group">
                <label>Total a preparar</label>
                <div class="input-wrapper">
                    <input type="number" id="totalMl" value="60" min="1">
                    <span class="unit">ml</span>
                </div>
            </div>
            <div class="form-group">
                <label>Nicotina Deseada</label>
                <div class="input-wrapper">
                    <input type="number" id="targetNic" value="3" step="0.5" min="0">
                    <span class="unit">mg</span>
                </div>
            </div>
            <div class="form-group">
                <label>Ratio VG Objetivo</label>
                <div class="input-wrapper">
                    <input type="number" id="targetVg" value="70" min="0" max="100">
                    <span class="unit">% VG</span>
                </div>
            </div>
            <div class="form-group">
                <label>Ratio PG Objetivo</label>
                <div class="input-wrapper">
                    <input type="number" id="targetPg" value="30" disabled>
                    <span class="unit">% PG</span>
                </div>
            </div>
        </div>

        <h3>2. Tu Base de Nicotina (Booster)</h3>
        <div class="grid-inputs">
            <div class="form-group">
                <label>Concentración</label>
                <div class="input-wrapper">
                    <input type="number" id="baseNic" value="20" min="0">
                    <span class="unit">mg</span>
                </div>
            </div>
            <div class="form-group">
                <label>Composición Base</label>
                <select id="baseNicComposition">
                    <option value="100PG">100% PG</option>
                    <option value="100VG">100% VG</option>
                    <option value="5050" selected>50/50 PG/VG</option>
                    <option value="7030">70/30 VG/PG</option>
                </select>
            </div>
        </div>

        <h3>3. Aromas / Moléculas</h3>
        <div id="aromasContainer" style="margin-bottom: 10px;">
            <div class="aroma-row">
                <input type="text" class="aroma-name" value="Aroma Principal">
                <div class="input-wrapper">
                    <input type="number" class="aroma-pct" value="10" min="0" max="100">
                    <span class="unit">%</span>
                </div>
                <button class="btn btn-danger" onclick="removeAroma(this)"><i class="fa-solid fa-trash"></i></button>
            </div>
        </div>
        <button class="btn btn-secondary" style="width: 100%;" onclick="addAroma()"><i class="fa-solid fa-plus"></i> Añadir Aroma</button>

        <button class="btn btn-primary" onclick="calcularReceta()"><i class="fa-solid fa-calculator"></i> Calcular e Imprimir</button>
    </div>

    <div class="panel" style="display: flex; flex-direction: column; justify-content: space-between;">
        <div>
            <h2>Resultados</h2>
            <table class="res-table">
                <thead>
                    <tr>
                        <th>Ingrediente</th>
                        <th>%</th>
                        <th>Mililitros (ml)</th>
                        <th>Gramos (g)</th>
                    </tr>
                </thead>
                <tbody id="resultBody">
                    <tr><td colspan="4" style="color: var(--text-muted); text-align: center; padding: 40px;">Introduce los datos y pulsa calcular.</td></tr>
                </tbody>
            </table>
        </div>

        <div>
            <h3><i class="fa-solid fa-bookmark"></i> Recetas Guardadas</h3>
            <div class="saved-recipes-list" id="savedRecipes">
                </div>
            <button class="btn btn-secondary" style="width: 100%; margin-top: 15px;" onclick="saveCurrentRecipe()"><i class="fa-solid fa-floppy-disk"></i> Guardar Receta Actual</button>
        </div>
    </div>
</div>

<script>
    // Densidades oficiales de la alquimia
    const D_VG = 1.26;
    const D_PG = 1.04;

    // Vincular PG y VG objetivos automáticamente
    document.getElementById('targetVg').addEventListener('input', function() {
        let val = Math.min(100, Math.max(0, parseFloat(this.value) || 0));
        document.getElementById('targetPg').value = 100 - val;
    });

    function addAroma(name = "Nuevo Aroma", pct = 5) {
        const container = document.getElementById('aromasContainer');
        const div = document.createElement('div');
        div.className = 'aroma-row';
        div.innerHTML = `
            <input type="text" class="aroma-name" value="${name}">
            <div class="input-wrapper">
                <input type="number" class="aroma-pct" value="${pct}" min="0" max="100">
                <span class="unit">%</span>
            </div>
            <button class="btn btn-danger" onclick="removeAroma(this)"><i class="fa-solid fa-trash"></i></button>
        `;
        container.appendChild(div);
    }

    function removeAroma(btn) {
        const rows = document.querySelectorAll('.aroma-row');
        if(rows.length > 1) {
            btn.parentElement.remove();
        } else {
            alert("Debes dejar al menos un ingrediente o aroma.");
        }
    }

    function calcularReceta() {
        const errorAlert = document.getElementById('errorAlert');
        errorAlert.style.display = 'none';

        // Obtención de Inputs principales
        const totalMl = parseFloat(document.getElementById('totalMl').value) || 0;
        const targetNic = parseFloat(document.getElementById('targetNic').value) || 0;
        const baseNic = parseFloat(document.getElementById('baseNic').value) || 0;
        const targetVgPct = parseFloat(document.getElementById('targetVg').value) || 0;
        const targetPgPct = 100 - targetVgPct;
        const nicComp = document.getElementById('baseNicComposition').value;

        if (totalMl <= 0) { displayError("La cantidad total debe ser mayor que 0."); return; }

        // 1. Cálculo de Nicotina necesaria
        let mlNic = 0;
        if (targetNic > 0) {
            if (baseNic <= 0) { displayError("La concentración de la base de nicotina debe ser mayor que 0."); return; }
            mlNic = (targetNic * totalMl) / baseNic;
        }

        if (mlNic > totalMl) {
            displayError("¡Error! La nicotina requerida supera el volumen total de la mezcla.");
            return;
        }

        // Desglose de PG/VG de la propia base de nicotina
        let nicPgPct = 0, nicVgPct = 0;
        if(nicComp === "100PG") { nicPgPct = 100; }
        else if(nicComp === "100VG") { nicVgPct = 100; }
        else if(nicComp === "5050") { nicPgPct = 50; nicVgPct = 50; }
        else if(nicComp === "7030") { nicVgPct = 70; nicPgPct = 30; }

        let mlNicPg = mlNic * (nicPgPct / 100);
        let mlNicVg = mlNic * (nicVgPct / 100);
        let gNic = (mlNicPg * D_PG) + (mlNicVg * D_VG);

        // 2. Cálculo de Aromas (Asumimos 100% PG que es el estándar de mercado)
        let mlAromasTotal = 0;
        let gAromasTotal = 0;
        let htmlAromas = '';
        
        const aromaRows = document.querySelectorAll('.aroma-row');
        let totalAromasPct = 0;

        for (let row of aromaRows) {
            let name = row.querySelector('.aroma-name').value || "Aroma";
            let pct = parseFloat(row.querySelector('.aroma-pct').value) || 0;
            totalAromasPct += pct;

            let mlAroma = totalMl * (pct / 100);
            let gAroma = mlAroma * D_PG; // Densidad estándar PG para aromas
            mlAromasTotal += mlAroma;
            gAromasTotal += gAroma;

            htmlAromas += `
                <tr>
                    <td><i class="fa-solid fa-cookie-bite" style="color:#f59e0b;"></i> ${name}</td>
                    <td>${pct.toFixed(1)}%</td>
                    <td>${mlAroma.toFixed(2)} ml</td>
                    <td>${gAroma.toFixed(2)} g</td>
                </tr>
            `;
        }

        if ((mlNic + mlAromasTotal) > totalMl) {
            displayError("La suma de nicotina y aromas supera los mililitros totales. Baja los porcentajes.");
            return;
        }

        // 3. Cuotas Objetivos de la Mezcla Total
        let mlVgObjetivo = totalMl * (targetVgPct / 100);
        let mlPgObjetivo = totalMl * (targetPgPct / 100);

        // 4. Calcular Ajuste de Líquidos Puros (Añadido final)
        // Restamos lo que ya introdujo la nicotina y los aromas (aromas = PG)
        let mlVgPuro = mlVgObjetivo - mlNicVg;
        let mlPgPuro = mlPgObjetivo - mlNicPg - mlAromasTotal;

        if (mlVgPuro < 0 || mlPgPuro < 0) {
            displayError(`Inconsistencia de Proporciones: Con la nicotina y aromas actuales ya superas el límite de tu ratio objetivo. No es posible formular esta mezcla exacta.`);
            return;
        }

        let gVgPuro = mlVgPuro * D_VG;
        let gPgPuro = mlPgPuro * D_PG;

        // Calcular Totales de control
        let totalGramos = gNic + gAromasTotal + gVgPuro + gPgPuro;
        let totalPct = (mlNic/totalMl*100) + totalAromasPct + (mlVgPuro/totalMl*100) + (mlPgPuro/totalMl*100);

        // Renderizar Tabla
        let finalHtml = '';
        if(mlNic > 0) {
            finalHtml += `<tr>
                <td><i class="fa-solid fa-skull-crossbones" style="color:var(--danger);"></i> Base Nicotina (${baseNic}mg)</td>
                <td>${((mlNic/totalMl)*100).toFixed(1)}%</td>
                <td>${mlNic.toFixed(2)} ml</td>
                <td>${gNic.toFixed(2)} g</td>
            </tr>`;
        }
        
        finalHtml += htmlAromas;

        finalHtml += `
            <tr>
                <td><i class="fa-solid fa-droplet" style="color:#3b82f6;"></i> VG Puro (Glicerina)</td>
                <td>${((mlVgPuro/totalMl)*100).toFixed(1)}%</td>
                <td>${mlVgPuro.toFixed(2)} ml</td>
                <td>${gVgPuro.toFixed(2)} g</td>
            </tr>
            <tr>
                <td><i class="fa-solid fa-vial" style="color:#a855f7;"></i> PG Puro (Propilenglicol)</td>
                <td>${((mlPgPuro/totalMl)*100).toFixed(1)}%</td>
                <td>${mlPgPuro.toFixed(2)} ml</td>
                <td>${gPgPuro.toFixed(2)} g</td>
            </tr>
            <tr class="total-row">
                <td>TOTAL</td>
                <td>${Math.round(totalPct)}%</td>
                <td>${totalMl.toFixed(1)} ml</td>
                <td>${totalGramos.toFixed(2)} g</td>
            </tr>
        `;

        document.getElementById('resultBody').innerHTML = finalHtml;
    }

    function displayError(msg) {
        const errorAlert = document.getElementById('errorAlert');
        errorAlert.innerText = msg;
        errorAlert.style.display = 'block';
    }

    // --- SISTEMA DE ALMACENAMIENTO (LOCALSTORAGE) ---
    function saveCurrentRecipe() {
        const name = document.getElementById('recipeName').value.trim();
        if(!name) { alert("Ponle un nombre a tu receta"); return; }

        // Recopilar aromas
        let aromas = [];
        document.querySelectorAll('.aroma-row').forEach(row => {
            aromas.push({
                name: row.querySelector('.aroma-name').value,
                pct: row.querySelector('.aroma-pct').value
            });
        });

        const recipeData = {
            name: name,
            totalMl: document.getElementById('totalMl').value,
            targetNic: document.getElementById('targetNic').value,
            baseNic: document.getElementById('baseNic').value,
            targetVg: document.getElementById('targetVg').value,
            baseNicComposition: document.getElementById('baseNicComposition').value,
            aromas: aromas
        };

        let recipes = JSON.parse(localStorage.getItem('vapeRecipes')) || [];
        // Evitar duplicados eliminando previa si se llama igual
        recipes = recipes.filter(r => r.name !== name);
        recipes.push(recipeData);
        
        localStorage.setItem('vapeRecipes', JSON.stringify(recipes));
        loadSavedRecipesList();
    }

    function loadSavedRecipesList() {
        const container = document.getElementById('savedRecipes');
        container.innerHTML = '';
        let recipes = JSON.parse(localStorage.getItem('vapeRecipes')) || [];

        if(recipes.length === 0) {
            container.innerHTML = '<span style="color:var(--text-muted); font-size:0.9rem;">No hay recetas guardadas.</span>';
            return;
        }

        recipes.forEach(r => {
            const div = document.createElement('div');
            div.className = 'recipe-item';
            div.innerHTML = `
                <span onclick="loadRecipe('${r.name}')">${r.name} (${r.targetVg}/${100 - r.targetVg})</span>
                <i class="fa-solid fa-trash-can" style="color:var(--danger); cursor:pointer;" onclick="deleteRecipe('${r.name}')"></i>
            `;
            container.appendChild(div);
        });
    }

    function loadRecipe(name) {
        let recipes = JSON.parse(localStorage.getItem('vapeRecipes')) || [];
        let r = recipes.find(recipe => recipe.name === name);
        if(!r) return;

        document.getElementById('recipeName').value = r.name;
        document.getElementById('totalMl').value = r.totalMl;
        document.getElementById('targetNic').value = r.targetNic;
        document.getElementById('baseNic').value = r.baseNic;
        document.getElementById('targetVg').value = r.targetVg;
        document.getElementById('targetPg').value = 100 - r.targetVg;
        document.getElementById('baseNicComposition').value = r.baseNicComposition;

        // Reconstruir aromas
        const container = document.getElementById('aromasContainer');
        container.innerHTML = '';
        r.aromas.forEach(aroma => {
            addAroma(aroma.name, aroma.pct);
        });

        calcularReceta();
    }

    function deleteRecipe(name) {
        let recipes = JSON.parse(localStorage.getItem('vapeRecipes')) || [];
        recipes = recipes.filter(r => r.name !== name);
        localStorage.setItem('vapeRecipes', JSON.stringify(recipes));
        loadSavedRecipesList();
    }

    // Inicialización al arrancar
    window.onload = function() {
        loadSavedRecipesList();
        calcularReceta(); // Cálculo por defecto inicial
    };
</script>
</body>
</html>

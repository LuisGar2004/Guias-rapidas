# Guias-rapidas
ULTRASONIDO TERAPÉUTICO CHATTANOOGA INTELECT TRANSPORT - Modelo 2782
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guía Rápida - Ultrasonido Terapéutico</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .guide-container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #2193b0, #6dd5ed);
            color: white;
            padding: 30px;
            text-align: center;
            position: relative;
        }
        
        .header::before {
            content: '🔊';
            font-size: 60px;
            position: absolute;
            top: 20px;
            left: 30px;
            opacity: 0.3;
        }
        
        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        
        .header .subtitle {
            font-size: 1.2em;
            opacity: 0.9;
            font-weight: 300;
        }
        
        .content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 0;
        }
        
        .left-panel {
            background: #f8fafc;
            padding: 30px;
        }
        
        .right-panel {
            background: white;
            padding: 30px;
        }
        
        .spec-box {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 20px;
            border-radius: 15px;
            margin-bottom: 25px;
        }
        
        .spec-box h3 {
            font-size: 1.3em;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .spec-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
            font-size: 0.95em;
        }
        
        .spec-item strong {
            color: #ffd700;
        }
        
        .steps-container h2 {
            color: #2d3748;
            font-size: 1.8em;
            margin-bottom: 25px;
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .step {
            background: white;
            border: 2px solid #e2e8f0;
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 20px;
            transition: all 0.3s ease;
            position: relative;
        }
        
        .step:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            border-color: #667eea;
        }
        
        .step-number {
            position: absolute;
            top: -15px;
            left: 20px;
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 1.2em;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        .step h4 {
            color: #2d3748;
            font-size: 1.2em;
            margin-bottom: 10px;
            margin-left: 50px;
        }
        
        .step-content {
            margin-left: 20px;
        }
        
        .step-list {
            list-style: none;
            padding: 0;
        }
        
        .step-list li {
            padding: 8px 0;
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 0.95em;
            color: #4a5568;
        }
        
        .step-list li::before {
            content: '✓';
            background: #48bb78;
            color: white;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 12px;
            font-weight: bold;
            flex-shrink: 0;
        }
        
        .warning-box {
            background: linear-gradient(135deg, #fed7d7, #feb2b2);
            border-left: 5px solid #e53e3e;
            padding: 15px;
            border-radius: 10px;
            margin: 20px 0;
        }
        
        .warning-box h4 {
            color: #742a2a;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .warning-box ul {
            color: #742a2a;
            margin-left: 20px;
        }
        
        .parameters-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        
        .param-card {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 15px;
            border-radius: 12px;
            text-align: center;
        }
        
        .param-card h5 {
            font-size: 1.1em;
            margin-bottom: 10px;
            color: #ffd700;
        }
        
        .param-card p {
            font-size: 0.9em;
            line-height: 1.4;
        }
        
        .maintenance-section {
            background: #f0fff4;
            border: 2px solid #68d391;
            border-radius: 15px;
            padding: 20px;
            margin-top: 25px;
        }
        
        .maintenance-section h3 {
            color: #22543d;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .footer {
            background: #2d3748;
            color: white;
            padding: 20px 30px;
            text-align: center;
        }
        
        .footer a {
            color: #90cdf4;
            text-decoration: none;
            font-weight: 500;
        }
        
        .footer a:hover {
            color: #63b3ed;
            text-decoration: underline;
        }
        
        @media (max-width: 768px) {
            .content {
                grid-template-columns: 1fr;
            }
            
            .parameters-grid {
                grid-template-columns: 1fr;
            }
            
            .header h1 {
                font-size: 2em;
            }
            
            .header::before {
                display: none;
            }
        }
        
        @media print {
            body {
                background: white;
            }
            
            .guide-container {
                box-shadow: none;
            }
            
            .step:hover {
                transform: none;
                box-shadow: none;
            }
        }
    </style>
</head>
<body>
    <div class="guide-container">
        <div class="header">
            <h1>ULTRASONIDO TERAPÉUTICO</h1>
            <div class="subtitle">CHATTANOOGA INTELECT TRANSPORT - Modelo 2782</div>
        </div>
        
        <div class="content">
            <div class="left-panel">
                <div class="spec-box">
                    <h3>⚙️ Especificaciones Técnicas</h3>
                    <div class="spec-item">
                        <span>Frecuencias:</span>
                        <strong>1 MHz | 3.3 MHz</strong>
                    </div>
                    <div class="spec-item">
                        <span>Cabezales:</span>
                        <strong>1, 2, 5, 10 cm²</strong>
                    </div>
                    <div class="spec-item">
                        <span>Intensidad continua:</span>
                        <strong>0-2.5 W/cm²</strong>
                    </div>
                    <div class="spec-item">
                        <span>Intensidad pulsada:</span>
                        <strong>0-3.0 W/cm²</strong>
                    </div>
                    <div class="spec-item">
                        <span>Duty Cycles:</span>
                        <strong>10%, 20%, 50%, continuo</strong>
                    </div>
                </div>
                
                <div class="warning-box">
                    <h4>⚠️ PRECAUCIONES IMPORTANTES</h4>
                    <ul>
                        <li>NUNCA mantener cabezal estático</li>
                        <li>Usar abundante gel conductor</li>
                        <li>Monitorear temperatura del cabezal</li>
                        <li>Verificar integridad de cables</li>
                    </ul>
                </div>
                
                <div class="parameters-grid">
                    <div class="param-card">
                        <h5>Condiciones Agudas</h5>
                        <p>0.5 W/cm²<br>Pulsado 20%<br>3-5 minutos</p>
                    </div>
                    <div class="param-card">
                        <h5>Condiciones Crónicas</h5>
                        <p>0.8-1.0 W/cm²<br>Continuo<br>5-10 minutos</p>
                    </div>
                    <div class="param-card">
                        <h5>Bursitis</h5>
                        <p>1-3 MHz<br>0.5-1.5 W/cm²<br>5-8 minutos</p>
                    </div>
                    <div class="param-card">
                        <h5>Epicondilitis</h5>
                        <p>3 MHz<br>0.8-1.2 W/cm²<br>Modo pulsado</p>
                    </div>
                </div>
            </div>
            
            <div class="right-panel">
                <div class="steps-container">
                    <h2>📋 Procedimiento Operativo</h2>
                    
                    <div class="step">
                        <div class="step-number">1</div>
                        <h4>Configuración Inicial</h4>
                        <div class="step-content">
                            <ul class="step-list">
                                <li>Encender con botón Power On/Off</li>
                                <li>Conectar cabezal apropiado (reconocimiento automático)</li>
                                <li>Seleccionar frecuencia apropiada</li>
                                <li>Configurar duty cycle y tiempo</li>
                                <li>Establecer intensidad inicial baja</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="step">
                        <div class="step-number">2</div>
                        <h4>Preparación del Paciente</h4>
                        <div class="step-content">
                            <ul class="step-list">
                                <li>Limpiar área con agua y jabón</li>
                                <li>Secar completamente la piel</li>
                                <li>Aplicar abundante gel conductor</li>
                                <li>Explicar procedimiento al paciente</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="step">
                        <div class="step-number">3</div>
                        <h4>Aplicación del Tratamiento</h4>
                        <div class="step-content">
                            <ul class="step-list">
                                <li>Colocar cabezal en contacto con piel</li>
                                <li>Presionar START (5 pitidos confirman inicio)</li>
                                <li>Mantener movimiento continuo 2-4 cm/seg</li>
                                <li>Monitorear indicadores LED</li>
                                <li>Ajustar parámetros según respuesta</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="step">
                        <div class="step-number">4</div>
                        <h4>Finalización</h4>
                        <div class="step-content">
                            <ul class="step-list">
                                <li>Limpiar cabezal con alcohol 70%</li>
                                <li>Desconectar equipo de alimentación</li>
                                <li>Documentar parámetros utilizados</li>
                                <li>Verificar que indicador "Head Over Temp" no esté activo</li>
                            </ul>
                        </div>
                    </div>
                </div>
                
                <div class="maintenance-section">
                    <h3>🔧 Mantenimiento Básico</h3>
                    <ul class="step-list">
                        <li>Limpiar cabezal con alcohol entre pacientes (obligatorio)</li>
                        <li>Verificar cables y conectores antes de cada uso</li>
                        <li>Comprobar funcionamiento de controles</li>
                        <li>Calibración anual por técnico certificado</li>
                    </ul>
                </div>
            </div>
        </div>
        
        <div class="footer">
            <p><strong>Manual Oficial:</strong> 
                <a href="https://enovis.com/sites/default/files/User%20Manual%20-%202782%20Transport%20Ultrasound.pdf" target="_blank">
                    Descargar Manual Técnico Completo
                </a>
            </p>
            <p style="margin-top: 10px; font-size: 0.9em; opacity: 0.8;">
                Cumple estándares ISO 13485 • Revisión: Enero 2025
            </p>
        </div>
    </div>
</body>
</html>

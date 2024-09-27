<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Informe exploración de datos Cambio Climático</title>
        <meta name="description" content="La OMS con las nuevas directrices de la calidad del aire tienen como objetivo evitar millones de muertes debidas a la contaminación del aire.">
        <link rel="icon" href="Imagenes/Escudo.jpg" type="image/jpeg"> <!-- Ruta corregida -->
        <style>
            table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
            }

            th, td {
                border: 1px solid #333;
                padding: 8px;
                text-align: center;
            }

            th {
                background-color: #f2f2f2;
            }

            caption {
                font-weight: bold;
                margin: 10px 0;
            }
            .image-description {
            text-align: center;
            font-size: 14px;
            color: #555;
            margin-top: 10px;
            }
            .center-img {
            display: block;
            margin-left: auto;
            margin-right: auto;
            }
            body {
                font-family: 'Times New Roman', Times, serif;
                margin: 0;
                padding: 0;
                background-color: #fff;
            }

            .cover-container {
                width: 100%;
                max-width: 800px;
                text-align: center;
                padding: 20px;
                margin-top: 50px;
            }

            h1 {
                font-size: 2em;
                font-weight: bold;
                margin-top: 200px;
            }

            .author {
                font-size: 1.5em;
                margin-top: 150px;
            }

            .institution {
                font-size: 1.5em;
                margin-top: 20px;
            }

            .course, .date {
                font-size: 1.2em;
                margin-top: 20px;
            }

            .cover-container {
                font-size: 12pt;
            }

            nav {
                background-color: #f4f4f4;
                padding: 10px;
                border-radius: 8px;
                margin-bottom: 20px;
                text-align: center;
            }

            nav a {
                margin-right: 15px;
                text-decoration: none;
                color: #3498db;
                font-weight: bold;
            }

            nav a:hover {
                text-decoration: underline;
            }

            section {
                padding: 20px;
                max-width: 800px;
                margin: 0 auto;
            }

            h2 {
                color: #2c3e50;
                margin-top: 50px;
            }

            p {
                font-size: 1.1em;
                color: #34495e;
                line-height: 1.6;
                text-align: left;
            }
        </style>
    </head>
    <body>
        <header>
            <nav>
                <a href="#Portada">Portada</a>
                <a href="#Introduccion">Introducción</a>
                <a href="#Resultados">Resultados</a>
                <a href="#Conclusiones">Conclusiones</a>
            </nav>
        </header>
        <section id="Portada" class="cover-container">
            <h1>Cambio Climático</h1>
            <!-- Nombre del autor -->
            <p class="authors">Juan Jose Ruiz Cardona<br>Pazos</p>
            <p class="institution">Universidad de Antioquia</p>
            <!-- Curso y profesor (opcional) -->
            <p class="course">Curso: Probabilidad e Inferencia Estadística<br>Profesor: Lorena Paola Brun Gonzalez</p>
        </section>


        <!-- Sección: Introducción -->
        <section id="Introduccion">
            <h2>Introducción</h2>
            <p>
                El cambio climático es uno de los desafíos más críticos que enfrenta la humanidad. Las variaciones en los patrones climáticos, impulsadas principalmente por las emisiones de gases de efecto invernadero, están afectando gravemente al medio ambiente, la biodiversidad y la vida humana.<br>

                Las nuevas directrices mundiales de la Oragnizacion Mundial de la Salud sobre la calidad del aire aportan pruebas claras del daño que la contaminación del aire inflinge a la salud humana en concentraciones aún más bajas de lo que se suponia hasta ahora.
                las directrices recomiendan nuevos niveles de calidad del aire para proteger la salud de la poblaciones mediante la reduccion de los niveles de los principales contaminates del aire , algunos de los cuales también contribuyen al cambio climatico.<br>
                La OMS junto con el Intituto de Hidrología , Meteorología y Estudios Ambientales (IDEAM) buscan estudiar como los tipos de energía , las politicas Ambientales , la conciencia social y la cantidad de dinero invertido en energia renovable , tiene relación con la 
                disminución de las Emisiones de C02 , deforestación y la cantidad de energía utilizada , el estudio se llevo a cabo en 200 regiones distintas de Colombia.
            </p>
        </section>

        <!-- Sección: Metodología -->
        <section id="Resultados">
            <h2>Resultados</h2>
            <p>
                Tabla con el resumen numérico de las variables cuantitativas.
            </p>
            <h3>Tabla de Resumen de Datos:</h3>
            <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%; text-align: center;">
                <thead>
                    <tr>
                        <th>Estadisticos</th>
                        <th>Emisiones_CO2</th>
                        <th>Deforestación</th>
                        <th>Uso_Energía</th>
                        <th>Inversión_Renovable</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>count</td>
                        <td>200.00000</td>
                        <td>200.000000</td>
                        <td>200.000000</td>
                        <td>200.000000</td>
                    </tr>
                    <tr>
                        <td>mean</td>
                        <td>23640.74500</td>
                        <td>3687.890000</td>
                        <td>51684.26000	</td>
                        <td>2312.770000</td>

                    </tr>
                    <tr>
                        <td>std</td>
                        <td>16591.23778</td>
                        <td>2811.579857</td>
                        <td>30068.77647	</td>
                        <td>1455.800751</td>
                    </tr>
                    <tr>
                        <td>min</td>
                        <td>1425.00000</td>
                        <td>117.000000</td>
                        <td>1762.00000</td>
                        <td>24.000000</td>
                    </tr>
                    <tr>
                        <td>25%</td>
                        <td>7739.00000</td>
                        <td>1159.000000</td>
                        <td>25647.25000	</td>
                        <td>957.750000</td>
                    </tr>
                    <tr>
                        <td>50%</td>
                        <td>22487.50000</td>
                        <td>3202.000000</td>
                        <td>50349.50000</td>
                        <td>2383.500000</td>
                    </tr>
                    <tr>
                        <td>75%</td>
                        <td>39453.25000</td>
                        <td>5662.250000</td>
                        <td>80979.75000	</td>
                        <td>3603.500000</td>
                    </tr>
                    <tr>
                        <td>max</td>
                        <td>49825.00000</td>
                        <td>9821.000000</td>
                        <td>99208.00000	</td>
                        <td>4996.000000</td>
                    </tr>
                    <tr>
                        <td>IQR</td>
                        <td>31714.25</td>
                        <td>4503.25</td>
                        <td>55332.5</td>
                        <td>2645.75</td>
                    </tr>
                    <tr>
                        <td>cv</td>
                        <td>70.18068923119318</td>
                        <td>76.23817026458381</td>
                        <td>58.17782139125851</td>
                        <td>62.94619658976644</td>
                    </tr>
                    <tr>
                        <td>skewness</td>
                        <td>0.08753333217256302</td>
                        <td>0.5842066095551393</td>
                        <td>-0.007226339864886639</td>
                        <td>0.09932145553145648</td>
                    </tr>
                </tbody>
            </table>
            <h3> Resumen numerico de Emisiones de CO2 por politica ambiental</h3>
            <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%; text-align: center;">
                <thead>
                    <th>Politica Ambiental</th>
                    <th>count</th>
                    <th>mean</th>
                    <th>std</th>
                    <th>min</th>
                    <th>25%</th>
                    <th>50%</th>
                    <th>75%</th>
                    <th>max</th>
                    <th>cv</th>
                    <th>skewness</th>
                </thead>
                <tr>
                    <td>Alta regulacion</td>
                    <td>78.0</td>
                    <td>22444.358974</td>
                    <td>16808.330707</td>
                    <td>1646.0</td>
                    <td>6597.5</td>
                    <td>14283.5</td>
                    <td>38962.00</td>
                    <td>49825.0</td>
                    <td>0.748889</td>
                    <td>0.173700</td>
                </tr>
                <tr>
                    <td>Baja regulacion</td>
                    <td>60.0</td>
                    <td>23443.333333</td>
                    <td>17111.530334</td>
                    <td>1425.0</td>
                    <td>7275.0</td>
                    <td>22668.0</td>
                    <td>40277.25</td>
                    <td>49381.0</td>
                    <td>0.729910</td>
                    <td>0.123360</td>
                </tr>
                <tr>
                    <td>Moderada regulacion</td>
                    <td>62.0</td>
                    <td>25336.919355</td>
                    <td>15918.185043</td>
                    <td>2059.0</td>
                    <td>11342.5</td>
                    <td>31383.0</td>
                    <td>39870.25</td>
                    <td>49496.0</td>
                    <td>0.628260</td>
                    <td>-0.037326</td>
                </tr>
            </table>
            <h3>Resumen numerico del uso de energía por conciencia social</h3>
            <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%; text-align: center;">
                <thead>
                    <th>Conciencia social</th>
                    <th>count</th>
                    <th>mean</th>
                    <th>std</th>
                    <th>min</th>
                    <th>25%</th>
                    <th>50%</th>
                    <th>75%</th>
                    <th>max</th>
                    <th>cv</th>
                    <th>skewness</th>
                </thead>
                <tr>
                    <td>Alta conciencia</td>
                    <td>71.0</td>
                    <td>48257.239437</td>
                    <td>28333.010691</td>
                    <td>2702.0</td>
                    <td>25853.0</td>
                    <td>47114.0</td>
                    <td>72416.0</td>
                    <td>98177.0</td>
                    <td>0.587125</td>
                    <td>0.110873</td>
                </tr>
                <tr>
                    <td>Baja conciencia</td>
                    <td>51.0</td>
                    <td>53765.666667</td>
                    <td>31642.574274</td>
                    <td>1762.0</td>
                    <td>24929.0</td>
                    <td>56620.0</td>
                    <td>81047.5</td>
                    <td>98029.0</td>
                    <td>0.588528</td>
                    <td>-0.272171</td>
                </tr>
                <tr>
                    <td>Moderada conciencia</td>
                    <td>78.0</td>
                    <td>53442.807692</td>
                    <td>30657.370434</td>
                    <td>4587.0</td>
                    <td>25853.0</td>
                    <td>48846.5</td>
                    <td>85579.0</td>
                    <td>99208.0</td>
                    <td>0.573648</td>
                    <td>0.041301</td>
                </tr>
            </table>
            <h3> Tabla de frecuencia para las variables cuantitativas</h3>
            <h4>Tabla de frecuencia para las emisiones de CO2</h4>
            <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%; text-align: center;">
                <thead>
                    <tr>
                        <th>Intervalo</th>
                        <th>Frecuencia</th>
                        <th>Frecuencia Relativa</th>
                        <th>Frecuencia Acumulada</th>
                        <th>Frecuencia Relativa Acumulada</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>[1425.0, 7475.0)</td>
                        <td>48</td>
                        <td>0.240</td>
                        <td>48</td>
                        <td>0.240</td>
                    </tr>
                    <tr>
                        <td>[7475.0, 13525.0)</td>
                        <td>41</td>
                        <td>0.205</td>
                        <td>89</td>
                        <td>0.445</td>
                    </tr>
                    <tr>
                        <td>[13525.0, 19575.0)</td>
                        <td>11</td>
                        <td>0.055</td>
                        <td>100</td>
                        <td>0.500</td>
                    </tr>
                    <tr>
                        <td>[19575.0, 25625.0)</td>
                        <td>0</td>
                        <td>0.000</td>
                        <td>100</td>
                        <td>0.500</td>
                    </tr>
                    <tr>
                        <td>[25625.0, 31675.0)</td>
                        <td>12</td>
                        <td>0.060</td>
                        <td>112</td>
                        <td>0.560</td>
                    </tr>
                    <tr>
                        <td>[31675.0, 37725.0)</td>
                        <td>28</td>
                        <td>0.140</td>
                        <td>140</td>
                        <td>0.700</td>
                    </tr>
                    <tr>
                        <td>[37725.0, 43775.0)</td>
                        <td>31</td>
                        <td>0.155</td>
                        <td>171</td>
                        <td>0.855</td>
                    </tr>
                    <tr>
                        <td>[43775.0, 49825.0)</td>
                        <td>28</td>
                        <td>0.140</td>
                        <td>199</td>
                        <td>0.995</td>
                    </tr>
                </tbody>
            </table>
            <h4>Distribución de Frecuencias: Deforestación</h4>
            <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%; text-align: center;">
                <thead>
                    <tr>
                        <th>Intervalo</th>
                        <th>Frecuencia</th>
                        <th>Frecuencia Relativa</th>
                        <th>Frecuencia Acumulada</th>
                        <th>Frecuencia Relativa Acumulada</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>[117.0, 1330.0)</td>
                        <td>56</td>
                        <td>0.280</td>
                        <td>56</td>
                        <td>0.280</td>
                    </tr>
                    <tr>
                        <td>[1330.0, 2543.0)</td>
                        <td>32</td>
                        <td>0.160</td>
                        <td>88</td>
                        <td>0.440</td>
                    </tr>
                    <tr>
                        <td>[2543.0, 3756.0)</td>
                        <td>23</td>
                        <td>0.115</td>
                        <td>111</td>
                        <td>0.555</td>
                    </tr>
                    <tr>
                        <td>[3756.0, 4969.0)</td>
                        <td>28</td>
                        <td>0.140</td>
                        <td>139</td>
                        <td>0.695</td>
                    </tr>
                    <tr>
                        <td>[4969.0, 6182.0)</td>
                        <td>19</td>
                        <td>0.095</td>
                        <td>158</td>
                        <td>0.790</td>
                    </tr>
                    <tr>
                        <td>[6182.0, 7395.0)</td>
                        <td>10</td>
                        <td>0.050</td>
                        <td>168</td>
                        <td>0.840</td>
                    </tr>
                    <tr>
                        <td>[7395.0, 8608.0)</td>
                        <td>19</td>
                        <td>0.095</td>
                        <td>187</td>
                        <td>0.935</td>
                    </tr>
                    <tr>
                        <td>[8608.0, 9821.0)</td>
                        <td>12</td>
                        <td>0.060</td>
                        <td>199</td>
                        <td>0.995</td>
                    </tr>
                </tbody>
            </table>
            <h4>Distribución de Frecuencias: Uso de Energía</h4>
            <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%; text-align: center;">
                <thead>
                    <tr>
                        <th>Intervalo</th>
                        <th>Frecuencia</th>
                        <th>Frecuencia Relativa</th>
                        <th>Frecuencia Acumulada</th>
                        <th>Frecuencia Relativa Acumulada</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>[1762.0, 13942.75)</td>
                        <td>30</td>
                        <td>0.150</td>
                        <td>30</td>
                        <td>0.150</td>
                    </tr>
                    <tr>
                        <td>[13942.75, 26123.5)</td>
                        <td>22</td>
                        <td>0.110</td>
                        <td>52</td>
                        <td>0.260</td>
                    </tr>
                    <tr>
                        <td>[26123.5, 38304.25)</td>
                        <td>26</td>
                        <td>0.130</td>
                        <td>78</td>
                        <td>0.390</td>
                    </tr>
                    <tr>
                        <td>[38304.25, 50485.0)</td>
                        <td>22</td>
                        <td>0.110</td>
                        <td>100</td>
                        <td>0.500</td>
                    </tr>
                    <tr>
                        <td>[50485.0, 62665.75)</td>
                        <td>20</td>
                        <td>0.100</td>
                        <td>120</td>
                        <td>0.600</td>
                    </tr>
                    <tr>
                        <td>[62665.75, 74846.5)</td>
                        <td>21</td>
                        <td>0.105</td>
                        <td>141</td>
                        <td>0.705</td>
                    </tr>
                    <tr>
                        <td>[74846.5, 87027.25)</td>
                        <td>31</td>
                        <td>0.155</td>
                        <td>172</td>
                        <td>0.860</td>
                    </tr>
                    <tr>
                        <td>[87027.25, 99208.0)</td>
                        <td>27</td>
                        <td>0.135</td>
                        <td>199</td>
                        <td>0.995</td>
                    </tr>
                </tbody>
            </table>
            <h4>Distribución de Frecuencias: Inversión en Energía Renovable</h4>
            <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%; text-align: center;">
                <thead>
                    <tr>
                        <th>Intervalo</th>
                        <th>Frecuencia</th>
                        <th>Frecuencia Relativa</th>
                        <th>Frecuencia Acumulada</th>
                        <th>Frecuencia Relativa Acumulada</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>[24.0, 645.5)</td>
                        <td>36</td>
                        <td>0.180</td>
                        <td>36</td>
                        <td>0.180</td>
                    </tr>
                    <tr>
                        <td>[645.5, 1267.0)</td>
                        <td>22</td>
                        <td>0.110</td>
                        <td>58</td>
                        <td>0.290</td>
                    </tr>
                    <tr>
                        <td>[1267.0, 1888.5)</td>
                        <td>32</td>
                        <td>0.160</td>
                        <td>90</td>
                        <td>0.450</td>
                    </tr>
                    <tr>
                        <td>[1888.5, 2510.0)</td>
                        <td>16</td>
                        <td>0.080</td>
                        <td>106</td>
                        <td>0.530</td>
                    </tr>
                    <tr>
                        <td>[2510.0, 3131.5)</td>
                        <td>29</td>
                        <td>0.145</td>
                        <td>135</td>
                        <td>0.675</td>
                    </tr>
                    <tr>
                        <td>[3131.5, 3753.0)</td>
                        <td>26</td>
                        <td>0.130</td>
                        <td>161</td>
                        <td>0.805</td>
                    </tr>
                    <tr>
                        <td>[3753.0, 4374.5)</td>
                        <td>19</td>
                        <td>0.095</td>
                        <td>180</td>
                        <td>0.900</td>
                    </tr>
                    <tr>
                        <td>[4374.5, 4996.0)</td>
                        <td>19</td>
                        <td>0.095</td>
                        <td>199</td>
                        <td>0.995</td>
                    </tr>
                </tbody>
            </table>
            <!-- Gráfico de Emisiones de CO2 -->
            <img src="Imagenes/hist_Emisiones.jpg" alt="Gráfico de Emisiones de CO2" class="center-img">
            <p class="image-description">Figura 1: Histograma de las Emisiones de CO2.</p>

            <!-- Gráfico de Deforestación -->
            <img src="Imagenes/hist_Deforestacion.jpg.png" alt="Gráfico de Deforestación" class="center-img">
            <p class="image-description">Figura 2: Histograma de la Deforestación.</p>

            <!-- Gráfico de Uso de Energía -->
            <img src="Imagenes/hist_Uso.jpg.png.jpg" alt="Gráfico del Uso de Energía" class="center-img">
            <p class="image-description">Figura 3: Histograma del Uso de Energía.</p>

            <!-- Gráfico de Inversión en Energía Renovable -->
            <img src="Imagenes/hist_Inversion.jpg" alt="Gráfico de Inversión en Energía Renovable" class="center-img">
            <p class="image-description">Figura 4: Histograma de la Inversión en Energía Renovable.</p>

            <!-- Gráfico por Tipo de Energía -->
            <img src="Imagenes/hist_Tipo.jpg" alt="Gráfico por Tipo de Energía" class="center-img">
            <p class="image-description">Figura 5: Histograma por Tipo de Energía.</p>

            <!-- Gráfico de Políticas Ambientales -->
            <img src="Imagenes/hist_Politica.jpg" alt="Gráfico de Políticas Ambientales" class="center-img">
            <p class="image-description">Figura 6: Histograma de las Políticas Ambientales.</p>

            <!-- Gráfico de Conciencia Social -->
            <img src="Imagenes/hist_Conciencia.jpg" alt="Gráfico de Conciencia Social" class="center-img">
            <p class="image-description">Figura 7: Histograma de la Conciencia Social.</p>

            <img src="Imagenes/box_Emisiones.jpg" alt="Gráfico de Emisiones de CO2" class="center-img">
            <p class="image-description">Figura 8: Gráfico de cajas de las Emisiones de CO2.</p>
        
            <!-- Gráfico de Cajas de Deforestación -->
            <img src="Imagenes/box_Deforestacion.jpg" alt="Gráfico de Deforestación" class="center-img">
            <p class="image-description">Figura 9: Gráfico de cajas de la Deforestación.</p>
        
            <!-- Gráfico de Cajas de Inversión en Energía Renovable -->
            <img src="Imagenes/box_Inversion.jpg" alt="Gráfico de Inversión en Energía Renovable" class="center-img">
            <p class="image-description">Figura 10: Gráfico de cajas de la Inversión en Energía Renovable.</p>
        
            <!-- Gráfico de Cajas de Uso de Energía -->
            <img src="Imagenes/box_Uso.jpg" alt="Gráfico del Uso de Energía" class="center-img">
            <p class="image-description">Figura 11: Gráfico de cajas del Uso de Energía.</p>

            <img src="Imagenes/box_Politica_Emisiones.jpg" alt="Gráfico de Emisiones por Politica" class="center-img">
            <p class="image-description">Figura 11: Gráfico de las emisiones de CO2 por Politica Ambiental.</p>

<!-- Tabla 1: Política Ambiental por Tipo de Energía -->
            <table>
                <caption>Distribución de Política Ambiental por Tipo de Energía</caption>
                <thead>
                    <tr>
                        <th>Tipo de Energía</th>
                        <th>Alta Regulación</th>
                        <th>Baja Regulación</th>
                        <th>Moderada Regulación</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Energía No Renovable</td>
                        <td>37</td>
                        <td>30</td>
                        <td>33</td>
                    </tr>
                    <tr>
                        <td>Energía Renovable</td>
                        <td>41</td>
                        <td>30</td>
                        <td>29</td>
                    </tr>
                    <tr>
                        <td>Total</td>
                        <td>78</td>
                        <td>60</td>
                        <td>62</td>
                    </tr>
                </tbody>
            </table>

            <table>
                <caption>Distribución de Conciencia Social por Tipo de Energía</caption>
                <thead>
                    <tr>
                        <th>Tipo de Energía</th>
                        <th>Alta Conciencia</th>
                        <th>Baja Conciencia</th>
                        <th>Media Conciencia</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Energía No Renovable</td>
                        <td>34</td>
                        <td>29</td>
                        <td>37</td>
                    </tr>
                    <tr>
                        <td>Energía Renovable</td>
                        <td>37</td>
                        <td>22</td>
                        <td>41</td>
                    </tr>
                    <tr>
                        <td>Total</td>
                        <td>71</td>
                        <td>51</td>
                        <td>78</td>
                    </tr>
                </tbody>
            </table>

            <table>
                <caption>Política Ambiental por Tipo de Energía</caption>
                <thead>
                    <tr>
                        <th>Política Ambiental</th>
                        <th>Energía No Renovable</th>
                        <th>Energía Renovable</th>
                        <th>Total</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Alta Regulación</td>
                        <td>37</td>
                        <td>41</td>
                        <td>78</td>
                    </tr>
                    <tr>
                        <td>Baja Regulación</td>
                        <td>30</td>
                        <td>30</td>
                        <td>60</td>
                    </tr>
                    <tr>
                        <td>Moderada Regulación</td>
                        <td>33</td>
                        <td>29</td>
                        <td>62</td>
                    </tr>
                    <tr>
                        <td>Total</td>
                        <td>100</td>
                        <td>100</td>
                        <td>200</td>
                    </tr>
                </tbody>
            </table>
            <table>
                <caption>Distribución de Conciencia Social por Política Ambiental</caption>
                <thead>
                    <tr>
                        <th>Conciencia Social</th>
                        <th>Alta Regulación</th>
                        <th>Baja Regulación</th>
                        <th>Moderada Regulación</th>
                        <th>Total</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Alta Conciencia</td>
                        <td>33</td>
                        <td>23</td>
                        <td>15</td>
                        <td>71</td>
                    </tr>
                    <tr>
                        <td>Baja Conciencia</td>
                        <td>21</td>
                        <td>11</td>
                        <td>19</td>
                        <td>51</td>
                    </tr>
                    <tr>
                        <td>Media Conciencia</td>
                        <td>24</td>
                        <td>26</td>
                        <td>28</td>
                        <td>78</td>
                    </tr>
                    <tr>
                        <td>Total</td>
                        <td>78</td>
                        <td>60</td>
                        <td>62</td>
                        <td>200</td>
                    </tr>
                </tbody>
            </table>
            <table>
                <caption>Conciencia Social por Tipo de Energía</caption>
                <thead>
                    <tr>
                        <th>Conciencia Social</th>
                        <th>Energía No Renovable</th>
                        <th>Energía Renovable</th>
                        <th>Total</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Alta Conciencia</td>
                        <td>34</td>
                        <td>37</td>
                        <td>71</td>
                    </tr>
                    <tr>
                        <td>Baja Conciencia</td>
                        <td>29</td>
                        <td>22</td>
                        <td>51</td>
                    </tr>
                    <tr>
                        <td>Media Conciencia</td>
                        <td>37</td>
                        <td>41</td>
                        <td>78</td>
                    </tr>
                    <tr>
                        <td>Total</td>
                        <td>100</td>
                        <td>100</td>
                        <td>200</td>
                    </tr>
                </tbody>
            </table>
            <img src="Imagenes/bar_Politica_Conciencia.png" alt="Gráfico de Inversión en Energía Renovable" class="center-img">
            <p class="image-description">Figura 12: Diagrama de barras de política ambiental por conciencia social</p>

            <img src="Imagenes/bar_Politica_Tipo.png" alt="Gráfico de Inversión en Energía Renovable" class="center-img">
            <p class="image-description">Figura 13: Diagrama de barras de política ambiental por tipo de energía</p>

            <img src="Imagenes/bar_Tipo_Conciencia.png" alt="Gráfico de Inversión en Energía Renovable" class="center-img">
            <p class="image-description">Figura 14: Diagrama de barras de tipo de energía por conciencia social</p>

            <img src="Imagenes/bar_Tipo_Politica.png" alt="Gráfico de Inversión en Energía Renovable" class="center-img">
            <p class="image-description">Figura 15: Diagrama de barras de tipo de energía por política ambiental</p>
            <h4> Tabla de correlacion de variables numericas</h4>
            <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 100%; text-align: center;">
                <thead>
                    <tr>
                        <th>Variables</th>
                        <th>Emisiones_CO2</th>
                        <th>Deforestacion</th>
                        <th>Uso_Energia</th>
                        <th>Inversion_Renovable</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Emisiones_CO2</td>
                        <td>1.000000</td>
                        <td>0.007619</td>
                        <td>0.830354</td>
                        <td>-0.098919</td>
                    </tr>
                    <tr>
                        <td>Deforestacion</td>
                        <td>0.007619</td>
                        <td>1.000000</td>
                        <td>0.049859</td>
                        <td>0.017638</td>
                    </tr>
                    <tr>
                        <td>Uso_Energia</td>
                        <td>0.830354</td>
                        <td>0.049859</td>
                        <td>1.000000</td>
                        <td>-0.055878</td>
                    </tr>
                    <tr>
                        <td>Inversion_Renovable</td>
                        <td>-0.098919</td>
                        <td>0.017638</td>
                        <td>-0.055878</td>
                        <td>1.000000</td>
                    </tr>
                </tbody>
            </table>
        </section>

        
        <section id="Conclusiones">
            <h2>Conclusiones</h2>
            <p>
                El análisis numérico de las variables cuantitativas relacionadas con el cambio climático revela varias tendencias importantes:
            </p>
            <p>
                1. **Emisiones de CO2**: La media de las emisiones de CO2 es de 23,640.75 unidades, con una desviación estándar de 16,591.24. La distribución de las emisiones muestra una ligera asimetría positiva (skewness de 0.09), indicando que hay algunos valores extremadamente altos. La variabilidad relativa (coeficiente de variación) es del 70.18%, lo que sugiere una alta dispersión en los datos.
            </p>
            <p>
                2. **Deforestación**: La media de la deforestación es de 3,687.89 unidades, con una desviación estándar de 2,811.58. La distribución es asimétrica positiva (skewness de 0.58), lo que indica la presencia de valores altos extremos. El coeficiente de variación es del 76.24%, mostrando una alta variabilidad en los datos.
            </p>
            <p>
                3. **Uso de Energía**: La media del uso de energía es de 51,684.26 unidades, con una desviación estándar de 30,068.78. La distribución es casi simétrica (skewness de -0.01), lo que sugiere una distribución equilibrada de los datos. El coeficiente de variación es del 58.18%, indicando una moderada dispersión.
            </p>
            <p>
                4. **Inversión en Energía Renovable**: La media de la inversión en energía renovable es de 2,312.77 unidades, con una desviación estándar de 1,455.80. La distribución es ligeramente asimétrica positiva (skewness de 0.10). El coeficiente de variación es del 62.95%, mostrando una dispersión moderada.
            </p>
            <p>
                5. **Política Ambiental**: Las emisiones de CO2 varían según el nivel de regulación ambiental. Las políticas de alta regulación tienen una media de emisiones de 22,444.36 unidades, mientras que las de baja y moderada regulación tienen medias de 23,443.33 y 25,336.92 unidades, respectivamente. La variabilidad es mayor en las políticas de alta regulación (cv de 0.75) en comparación con las de baja y moderada regulación.
            </p>
            <p>
                6. **Conciencia Social**: El uso de energía también varía según el nivel de conciencia social. Las regiones con alta conciencia social tienen un uso medio de energía de 48,257.24 unidades, mientras que las regiones con baja y moderada conciencia tienen usos medios de 53,765.67 y 53,442.81 unidades, respectivamente. La variabilidad es similar en todos los niveles de conciencia social.
            </p>
            <p>
                7. **Correlaciones**: Las emisiones de CO2 están altamente correlacionadas con el uso de energía (correlación de 0.83), lo que sugiere que a mayor uso de energía, mayores son las emisiones de CO2. La deforestación y la inversión en energía renovable tienen correlaciones bajas con las demás variables, indicando que estos factores no están fuertemente relacionados con las emisiones de CO2 o el uso de energía.
            </p>
            <p>Las políticas de alta regulación ambiental muestran una media de emisiones de CO2 de 22,444.36 unidades, con una desviación estándar de 16,808.33. La variabilidad relativa (cv) es de 0.75, y la asimetría (skewness) es de 0.17, indicando una ligera tendencia hacia valores más altos.</p>
            <p>Las políticas de baja regulación tienen una media de emisiones de CO2 de 23,443.33 unidades, con una desviación estándar de 17,111.53. El coeficiente de variación es de 0.73, y la asimetría es de 0.12, indicando una distribución ligeramente sesgada hacia valores más altos.</p>
            <p>Las políticas de moderada regulación presentan una media de emisiones de CO2 de 25,336.92 unidades, con una desviación estándar de 15,918.19. El coeficiente de variación es de 0.63, y la asimetría es de -0.04, sugiriendo una distribución casi simétrica.</p>
            <p>
                En general, las políticas de alta y baja regulación ambiental tienen medias de emisiones de CO2 relativamente similares, pero la alta regulación muestra una mayor variabilidad en las emisiones. Las políticas de moderada regulación tienen una media de emisiones ligeramente superior, pero con menor variabilidad y una distribución más equilibrada. La alta variabilidad en las políticas de alta y baja regulación sugiere que, aunque las políticas estrictas pueden reducir las emisiones en algunos casos, no siempre son consistentes en su efectividad. La menor variabilidad en las políticas de moderada regulación podría indicar un enfoque más equilibrado y posiblemente más sostenible a largo plazo.
            </p>
            <p>Las regiones con alta conciencia social tienen un uso medio de energía de 48,257.24 unidades, con una desviación estándar de 28,333.01. La variabilidad relativa (cv) es de 0.59, y la asimetría (skewness) es de 0.11, indicando una distribución ligeramente sesgada hacia valores más altos.</p>
            <p>Las regiones con baja conciencia social tienen un uso medio de energía de 53,765.67 unidades, con una desviación estándar de 31,642.57. El coeficiente de variación es de 0.59, y la asimetría es de -0.27, indicando una distribución ligeramente sesgada hacia valores más bajos.</p>
            <p>Las regiones con moderada conciencia social tienen un uso medio de energía de 53,442.81 unidades, con una desviación estándar de 30,657.37. El coeficiente de variación es de 0.57, y la asimetría es de 0.04, sugiriendo una distribución casi simétrica.</p>
            <p>
                En general, el uso de energía varía según el nivel de conciencia social. Las regiones con alta conciencia social tienden a tener un uso de energía ligeramente menor y una distribución más equilibrada en comparación con las regiones de baja y moderada conciencia social. La variabilidad es similar en todos los niveles de conciencia social, lo que sugiere que la conciencia social puede influir en el uso de energía, pero otros factores también juegan un papel importante.
            </p>
            <p>
                En resumen, el análisis numérico destaca la importancia de las políticas ambientales y la conciencia social en la gestión de las emisiones de CO2 y el uso de energía. Las políticas de alta regulación y una mayor conciencia social parecen estar asociadas con menores emisiones y un uso más eficiente de la energía.
            </p>
            <h4>Interpretaciones de las Tablas de Frecuencia</h4>
            <p>Emisiones de CO2: La mayoría de las emisiones de CO2 se concentran en los intervalos más bajos, con un 44.5% de las observaciones acumuladas hasta el segundo intervalo ([7475.0, 13525.0)). Esto sugiere que la mayoría de los países tienen emisiones relativamente bajas, aunque hay una minoría significativa con emisiones mucho más altas.</p>
            <p>Deforestación: La deforestación muestra una distribución más dispersa, con un 28% de las observaciones en el primer intervalo ([117.0, 1330.0)) y una acumulación gradual en los intervalos siguientes. Esto indica que la deforestación varía ampliamente entre los países.</p>
            <p>Uso de Energía: El uso de energía está más concentrado en los intervalos medios y altos, con un 50% de las observaciones acumuladas hasta el cuarto intervalo ([38304.25, 50485.0)). Esto sugiere que muchos países tienen un uso de energía moderado a alto.</p>
            <p>Inversión en Energía Renovable: La inversión en energía renovable está más concentrada en los intervalos más bajos, con un 45% de las observaciones acumuladas hasta el tercer intervalo ([1267.0, 1888.5)). Esto indica que la mayoría de los países invierten relativamente poco en energía renovable, aunque hay algunos con inversiones significativamente mayores.</p>
            <h4>Análisis Univariado y Bivariado para Variables Cualitativas</h4>
            <p>Distribución de Política Ambiental por Tipo de Energía: La mayoría de las políticas ambientales de alta regulación se aplican a la energía renovable (41 casos), mientras que la energía no renovable tiene 37 casos de alta regulación. Esto sugiere un enfoque más estricto en la regulación de la energía renovable.</p>
            <p>Distribución de Conciencia Social por Tipo de Energía: La alta conciencia social es más frecuente en la energía renovable (37 casos) en comparación con la energía no renovable (34 casos). Esto indica una mayor conciencia social en el uso de energías renovables.</p>
            <p>Política Ambiental por Tipo de Energía: Las políticas de alta regulación son más comunes en la energía renovable (41 casos) que en la energía no renovable (37 casos). Las políticas de baja y moderada regulación están distribuidas de manera similar entre ambos tipos de energía.</p>
            <p>Distribución de Conciencia Social por Política Ambiental: La alta conciencia social es más común en las políticas de alta regulación (33 casos), seguida por las políticas de moderada regulación (28 casos) y baja regulación (23 casos). Esto sugiere que una mayor regulación ambiental está asociada con una mayor conciencia social.</p>
            <p>Distribución de Conciencia Social por Política Ambiental: La alta conciencia social es más común en las políticas de alta regulación (33 casos), seguida por las políticas de moderada regulación (28 casos) y baja regulación (23 casos). Esto sugiere que una mayor regulación ambiental está asociada con una mayor conciencia social.</p>
        </section>

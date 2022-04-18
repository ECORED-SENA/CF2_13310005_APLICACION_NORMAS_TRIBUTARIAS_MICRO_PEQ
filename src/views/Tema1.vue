<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Responsabilidad Tributaria
    p.mb-5 En Colombia, la responsabilidad tributaria depende de varios aspectos, estos se mencionan en el siguiente video:
    .row.justify-content-center
      .col-lg-10
        figure.mb-5
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .bloque-texto-a.color-secundario.p-4.p-md-4.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-3.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/tema1/img1.svg', style="width: 250px").m-auto
        .col-lg-9
          .bloque-texto-a__texto.p-4
            p #[b Es importante tener en cuenta que el Decreto 957 del 5 de junio del 2019] es expedido por el gobierno nacional, en cabeza del Ministerio de Comercio, Industria y Turismo, por medio del cual se realizaron unas nuevas clasificaciones específicamente relacionadas con sector económico al que pertenecen las compañías y relaciona nuevamente el total de ingresos producto del desarrollo de sus actividades ordinarias, de la siguiente manera (ver tabla 1):
    .titulo-sexto.color-acento-contenido.mb-5
      p.mb-0 #[b Tabla 1.] Clasificación de las empresas según Decreto 957 del 5 de junio de 2019.
    .tabla-b.color-acento-contenido.mb-5
      .tabla-b__header
        p.mb-0 Ingresos en UVT (unidades de valor tributario) de actividades ordinarias según sector económico
      table
        caption Nota. Sena (2022).
        tr(style="background-color: #F5C573")
          td Sector /<br>Tamaño de la empresa
          td Microempresa
          td Pequeña
          td Mediana
          td Grande
        tr
          td Manufactura
          td.text-small Menores o iguales a 23.563.
          td.text-small Mayores a 23.563 y menores o iguales a 204.995.
          td.text-small Mayores a 204.995 y menores o iguales a 1'736.565.
          td.text-small Mayores a 1'736.565.
        tr
          td Servicios
          td.text-small Menores o iguales a 32.988.
          td.text-small Mayores a 32.988 y menores o iguales a 131.951.
          td.text-small Mayores a 131.951 y menores o iguales a 483.034.
          td.text-small Mayores a 483.034.
        tr
          td Comercio
          td.text-small Menores o iguales a 44.769.
          td.text-small Mayores a 44.769 y menores o iguales a 431.196.
          td.text-small Mayores a 431.196 y menores o iguales a 2.160.692.
          td.text-small Mayores a 2.160.692.
        tr
          td Otras actividades de comercio
          td.text-small Menores o iguales a 23.563.
          td.text-small Mayores a 23.563 y menores o iguales a 204.995.
          td.text-small Mayores a 204.995 y menores o iguales a 1'736.565.
          td.text-small Mayores a 1'736.565.
    #t_1_1.pt-5
    .titulo-segundo.color-secundario
      h2 1.1. Régimen Tributario
    p.mb-5 Con relación a los regímenes tributarios que se aplican en Colombia, se debe reconocer a tres de ellos:
    .row.justify-content-center.mb-5
      .col-lg-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = true")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img2.svg')})`}")
            .tarjeta-flip__contenido.bg-color1.p-4.p-xl-5
              h1 Responsables de IVA:
              p Como primera medida recordemos que la sigla IVA quiere decir Impuesto al Valor Agregado. Este grupo de contribuyentes anteriormente se conocían como Régimen Común, a partir de la expedición de la ley 1943 de 2018, pasó a llamarse responsables del impuesto a las ventas. Básicamente a este régimen pertenecen las personas jurídicas o empresas y las personas naturales que no cumplan con los requisitos consagrados en el artículo 437 en su parágrafo 3, del estatuto tributario.
      .col-lg-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-seterciario(@mouseover="indicadorTarjetaFlip = true")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img3.svg')})`}")
            .tarjeta-flip__contenido.bg-color2.p-4.p-xl-5
              h1 No responsables de IVA:
              p Aquí se agrupan todas las personas naturales que no son responsables del IVA, es decir, que sí cumplan con las condiciones del estatuto anteriormente mencionado. Un aspecto muy importante a tener en cuenta, es que aquí se pueden comercializar productos y servicios gravados con el impuesto de IVA, sin embargo, al no superar los topes establecidos, son considerados no responsables del impuesto.
      .col-lg-4.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-seterciario(@mouseover="indicadorTarjetaFlip = true")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema1/img4.svg')})`}")
            .tarjeta-flip__contenido.bg-color2.p-4.p-xl-5
              h1 Régimen tributario especial:
              p A este régimen pertenecen un grupo de empresas que desarrollan su objeto social sin perseguir el lucro. Aquí se integran unas normas tributarias especiales que son aplicables exclusivamente a algunas entidades. Es el caso de las ESAL, tales como las asociaciones, fundaciones, corporaciones, entre otras.
    .separador.mb-5
    #t_1_2
    .titulo-segundo.color-secundario
      h2 1.2. Impuestos
    .row.mb-5
      .col-lg-4.mb-4
        figure
          img(src='@/assets/curso/tema1/img5.svg', style="width: 220px").m-auto
      .col-lg-8
        .dual-txt-deco
          p(style="position: relative; z-index: 1;") Los impuestos en Colombia son principalmente tributos que se cancelan tanto por  personas naturales como las jurídicas al fisco o Estado, para poder suplir las necesidades básicas o el gasto público. Es decir, así como las empresas tienen su estructura financiera en donde producto del desarrollo de su actividad económica obtienen ingresos y a su vez con estos deben cubrir sus gastos o erogaciones para poder subsistir, así mismo el estado obtiene sus ingresos producto de los impuestos que se recaudan.
          p Existen impuestos de la directriz nacional los cuales se pagan por parte de los emprendedores y/o empresas directamente a la administración nacional, por ejemplo, el impuesto al valor agregado (IVA), el impuesto de renta y complementario y el gravamen a los movimientos financieros (GMF) o también conocido como 4x1000.
      .col-12
        p Por su parte algunos impuestos reconocidos del orden departamental como lo son el impuesto al consumo, y el impuesto de registro. Finalmente, también se encuentran impuestos recaudados directamente por los municipios como lo son el impuesto de industria y comercio, el predial, entre otros.
    .row.bg-color1.mb-4
      .col-12.py-5
        .row.justify-content-center
          .col-10
            h3 Elementos de un impuesto
            p.mb-5 Existen cinco elementos importantes en los impuestos, a continuación se presentan:
            .row
              .col-lg-3
                figure
                  img(src='@/assets/curso/tema1/img1.png', style="width: 420px").m-auto
              .col-lg-9.bg-color2
                .py-4.ps-4.pe-5
                  TabsA.color-acento-botones
                    .tarjeta.color-acento-botones.p-4(titulo="Sujeto activo")
                      p Es el estado, quien, por medio de una o varias entidades de su subordinación, establece las reglas de juego para administrar y controlar los impuestos.
                    .tarjeta.color-acento-botones.p-4(titulo="Sujeto pasivo")
                      p Es el contribuyente, es decir toda persona natural o jurídica que está en la obligación de pagar el impuesto. Es decir, es quien crea el impuesto mediante el desarrollo de una actividad gravada con el mismo.
                    .tarjeta.color-acento-botones.p-4(titulo="Hecho<br>generador")
                      p Es la actuación de comprar y/o vender un producto, o prestar un servicio, lo cual conlleva a adquirir un compromiso fiscal.
                    .tarjeta.color-acento-botones.p-4(titulo="Base gravable")
                      p Es el valor monetario al cual se le aplica la tasa establecida para el impuesto.
                    .tarjeta.color-acento-botones.p-4(titulo="Tarifa")
                      p Es la cantidad porcentual que debe aplicarse a la base gravable.
    .row.bg-color3.mb-4
      .col-12.py-5
        .row.justify-content-center
          .col-10
            h3 Clasificación de los impuestos
            p.mb-5 Los impuestos se clasifican en directos e indirectos de la siguiente manera (ver figura 1):
            .titulo-sexto.color-acento-contenido.mb-5
              p.mb-0 #[b figura 1.] Clasificación de los impuestos
            figure
              img(src='@/assets/curso/tema1/img6.svg', style="width: 1020px").m-auto
    .row.bg-color1.mb-5
      .col-12.py-5
        .row.justify-content-center
          .col-10
            h3 Principios de los impuestos
            p En el Art. 363 de la Constitución Política se establecen las características principales del sistema tributario.
            .row
              .col-lg-3
                figure
                  img(src='@/assets/curso/tema1/img2.png', style="width: 420px").m-auto
              .col-lg-9.bg-color2
                .py-4.ps-4.pe-5
                  TabsA.color-acento-botones
                    .tarjeta.color-acento-botones.p-4(titulo="Eficiencia")
                      p Los impuestos no deben alterar el comportamiento económico del país, esto debido a que se corren riesgos de tipo económico. El objetivo del estado es recaudar ingresos para sufragar sus necesidades, pero siempre buscando ser eficientes con bajos costos de las actividades, sin afectar la economía de las personas.
                    .tarjeta.color-acento-botones.p-4(titulo="Equidad")
                      p Los impuestos se dividen equitativamente entre todos los contribuyentes (persona natural o jurídica), sin sobrecargas.
                    .tarjeta.color-acento-botones.p-4(titulo="Progresividad")
                      p Los impuestos se cobran de acuerdo al total de ingresos de la persona. Lo ideal sería que los contribuyentes con ingresos importantes paguen más que los contribuyentes con menores oportunidades económicas.
    .separador.mb-5
    #t_1_3
    .titulo-segundo.color-secundario
      h2 1.3 Tipos de impuestos
    p.mb-5 En el país existen dos tipos de impuestos que son los nacionales y los del orden departamental y municipal. #[b A continuación, se hace mención de los impuestos más importantes y que se deben considerar a la hora de crear una micro o pequeña empresa]:
    .row.justify-content-center
      .col-lg-8
        TabsB.color-acento-contenido.mb-5
          .py-4.py-md-5(titulo="Impuestos nacionales" :icono="require('@/assets/curso/tema1/img7.svg')")
            .row
              .col-12
                p A continuación, se dará una breve descripción de algunos impuestos del orden nacional (ver tabla 2):
                .col-auto
                  a.boton.color-acento-botones.indicador__container(@click="modal1 = true")
                    span Ver Tabla
                    i.fas.fa-search-plus(style="color: #EF9F14")
                    .indicador--click(v-if="mostrarIndicador")
          .py-4.py-md-5(titulo="Impuestos departamentales y/o municipales" :icono="require('@/assets/curso/tema1/img7.svg')")
            .row
              .col-12
                p Estos impuestos se definen desde las asambleas departamentales o desde los concejos municipales según cada caso. A continuación, se hace mención a los impuestos de estos tipos, o al menos los más importantes y que se deben tener en considerar a la hora de crear una micro o pequeña empresa (ver tabla 3):
                .col-auto
                  a.boton.color-acento-botones.indicador__container(@click="modal2 = true")
                    span Ver Tabla
                    i.fas.fa-search-plus(style="color: #EF9F14")
                    .indicador--click(v-if="mostrarIndicador")
    ModalA(:abrir-modal.sync="modal1")
      .row.align-items-center
        .col-12
          .tabla-b.color-acento-contenido.mb-5
            .tabla-b__header
              p.mb-0 Impuestos nacionales
            table
              caption Nota. Sena (2022).
              tr(style="background-color: #F5C573")
                th Impuesto
                th Descripción
              tr
                td Impuesto de renta y complementarios para personas naturales y jurídicas.
                td
                  p Corresponde al pago porcentual que realizan los contribuyentes, teniendo como base los beneficios fiscales que se obtuvieron, en el año anterior a la declaración, conocido como periodo gravable. 
                  p Para determinar el monto del impuesto sobre la renta, primero es necesario depurar los ingresos descontando de ellos los costos o gastos que procedan fiscalmente para determinar finalmente la renta líquida gravable. Esta práctica de depuración se debe realizar individualmente para cada tipo de contribuyente y para cada caso individual.
              tr
                td Impuesto al valor agregado #[b IVA].
                td El impuesto al valor agregado o impuesto sobre las ventas, como su nombre lo indica, es un valor que se adiciona en el momento en que se comercializa un producto o servicio gravado con IVA, por parte de una persona natural o jurídica que sea responsable de facturar y cobrar este impuesto. En Colombia en la multiplicidad de productos y servicios que existen, se encuentran bienes y servicios gravados, exentos y excluidos, los cuales se encuentran consagrados en la ley correspondiente.
              tr
                td Retención en la fuente a título de renta y de IVA.
                td La retención en la fuente a título de renta y de IVA, funciona como un mecanismo de cobro anticipado de estos impuestos, realizado por el gobierno nacional mediante la intermediación de personas naturales y jurídicas que hacen las veces de agentes de retención, sencillamente estos terceros lo que hacen es retener de los pagos que deben realizar a sus proveedores o prestadores de servicios, parte de sus ingresos cuando a ello hubiere lugar, y posteriormente consignarlos al estado. Con lo anterior queda claro, que más que un impuesto es un cobro anticipado de un tributo.
              tr
                td Impuesto al consumo.
                td El impuesto al consumo se detalla en el artículo 512-1 del Estatuto Tributario. Básicamente se cobra sobre el suministro o venta de un producto o servicio que no es considerado esencial y por lo tanto, no se incluye como producto de la canasta familiar. Por ejemplo, el servicio de restaurante, vehículos automóviles de tipo familiar, servicio de telefonía móvil, entre otros.
              tr
                td Impuesto al patrimonio.
                td El impuesto al patrimonio se crea por medio del cambio al artículo 292-2 del Estatuto Tributario, para revivir lo que antes se conocía como impuesto a la riqueza. A partir del periodo gravable 2022 no se existe el impuesto al patrimonio, debido a que la Ley 2155 de 2021, también conocida como ley de inversión social, no dio continuidad a dicho impuesto. En este documento se hace mención a este impuesto, debido a que se ha convertido en  habitual y por consiguiente, es muy importante para los emprendedores de las micro y pequeñas empresas, tener conocimiento  sobre este impuesto que en cualquier reforma tributaria podría volver a renacer.
              tr
                td Gravamen a los movimientos financieros (GMF)
                td Este impuesto está presente en nuestros movimientos financieros desde el 1 de enero de 2001 y se impuso sobre la realización de transacciones financieras con bancos. También se conoce como 4x1000 (muy a pesar de que fue creado inicialmente como el 2x1000), su recaudo es responsabilidad de los bancos, es decir, que son intermediarios del impuesto, y posteriormente estos recursos son girados a la cuenta estatal.
    ModalA(:abrir-modal.sync="modal2")
      .row.align-items-center
        .col-12
          .tabla-b.color-acento-contenido.mb-5
            .tabla-b__header
              p.mb-0 Impuestos departamentales y/o municipales
            table
              caption Nota. Sena (2022).
              tr(style="background-color: #F5C573")
                th Impuesto
                th Concepto
              tr
                td ICA
                td También conocido como Impuesto de Industria y Comercio es un tributo municipal para el desempeño de funciones industriales, comerciales o de servicios creadas en cada municipio. Este recaudo se realiza con base en los ingresos que se obtengan en el municipio, ya sea directa o indirectamente, de manera habitual o esporádicamente, con local comercial o sin este. Dentro de este impuesto normalmente también se recaudan la sobretasa bomberil y el impuesto de avisos y tableros, si así lo contempla el municipio en donde se esté declarando.
              tr
                td Impuesto predial
                td El impuesto predial se cobra a los bienes raíces ubicados en cualquier región del orden nacional. Este impuesto se factura a partir del valor de la propiedad o avalúo catastral según su ubicación, número de pisos, área de construcción y tipo de propiedad, por nombrar algunos factores que se toman en consideración. Se utilizan distintas tarifas en cada municipio en particular dependiendo del estrato, entre otros aspectos. Para el caso de las micro y pequeñas empresas se cancelaría si para efectos del desarrollo del objeto social, se contará dentro de la estructura de los activos, con una propiedad raíz que figure a nombre de la empresa.
              tr
                td Impuesto vehicular
                td El impuesto vehicular corresponde a un pago anual de cierta cantidad monetaria, originado por poseer un automóvil que cumpla con los requisitos para movilizarse en la red vial y esté registrado en cualquier ciudad del territorio. De igual forma, se consideraría para las micro y pequeñas empresas, siempre y cuando el vehículo figure en cabeza de la empresa.
    .separador.mb-5
    #t_1_4
    .titulo-segundo.color-secundario
      h2 1.4 Tipos de formatos
    .bloque-texto-a.color-primario.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-3.mb-4.mb-lg-0
        .col-lg-9
          .bloque-texto-a__texto.p-4
            p Todo contribuyente que debe declarar y/o pagar impuestos nacionales lo debe realizar en los documentos asignados para ello. En el caso de cada micro o pequeña empresa se debe analizar todas y cada una de las responsabilidades que adquieren al momento de constituirse, para ello se recomienda si se desconoce el tema normativo, buscar asesoría para evitar multas y sanciones. #[b A continuación, se relacionan los formularios que actualmente tiene vigentes la DIAN para su respectivo diligenciamiento, si a ello hubiere lugar (ver tabla 3):]
    .titulo-sexto.color-acento-contenido.mb-5
      p.mb-0 #[b Tabla 2.] Formatos de impuestos
    .tabla-b.color-acento-contenido.mb-5
      .tabla-b__header
        p.mb-0 Formatos de impuestos
      table
        caption Nota. Sena (2022).
        tr(style="background-color: #F5C573")
          th(style="width: 14%") Formato
          th Nombre del formato
          th Normatividad
        tr
          td 110
          td Declaración de renta y complementario para personas jurídicas y asimiladas y personas naturales y asimiladas no residentes y sucesiones ilíquidas de causantes no residentes o de ingresos y patrimonio para entidades obligadas a declarar.
          td Resolución 011 de 2021.
        tr
          td 120
          td Declaración informativa de precios transferencia.
          td Resolución 00019 de 2020.
        tr
          td 150
          td Declaración de renta por cambio de la titularidad de la inversión extranjera directa y enajenaciones indirectas.
          td Resolución 000018 del 17 de febrero de 2021.
        tr
          td 160
          td Declaración anual de activos en el exterior.
          td Resolución 4 de enero 15 de 2019.
        tr
          td 210
          td Declaración de renta y complementario personas naturales y asimiladas de residentes y sucesiones ilíquidas de causantes residentes.
          td Resolución 000022 de marzo 5 de 2021.
        tr
          td 220
          td Certificado de ingresos y retenciones por rentas de trabajo y de pensiones Año gravable 2020.
          td Resolución 0117 de diciembre 30 de 2020.
        tr
          td 2593
          td Recibo electrónico del SIMPLE.
          td Resolución 000025 de marzo 19 de 2021.
        tr
          td 260
          td Declaración anual consolidada.
          td Resolución 000071 de 11 Agosto 2021.
        tr
          td 300
          td Declaración del impuesto sobre las ventas – IVA.
          td Resolución 00019 de marzo 10 de 2020.
        tr
          td 310
          td Declaración impuesto nacional al consumo.
          td Resolución 16 de marzo 7 de 2019.
        tr
          td 325
          td Declaración del impuesto sobre las ventas - IVA de  prestadores de servicios desde el exterior.
          td Resolución 69 de diciembre 28 de 2018.
        tr
          td 350
          td Declaración de retenciones en la fuente.
          td Resolución 000009 de febrero 5 de 2021.
        tr
          td 400
          td Formulario para liquidar y consignar el aporte especial de las notarías para la administración de justicia.
          td Resolución 4 de enero 15 de 2019.
        tr
          td 410
          td Declaración semanal gravamen a los movimientos financieros.
          td Resolución 4 de enero 15 de 2019.
        tr
          td 420
          td Declaración impuesto al patrimonio.
          td Resolución 000074 de 2 de julio del 2020.
        tr
          td 430
          td Declaración impuesto nacional a la gasolina y ACPM.
          td Resolución 4 de enero 15 de 2019.
        tr
          td 435
          td Impuesto nacional al carbono.
          td Resolución 4 de enero 15 de 2019.
        tr
          td 490
          td Recibo oficial de pago impuestos nacionales.
          td Resolución 4 de enero 15 - Resolución 12 de febrero 7 y Resolución 55 de septiembre 9 de 2019.
        tr
          td 500
          td Declaración de importación.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 510
          td Declaración de importación simplificada.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 520
          td Declaración para la finalización de los sistemas especiales de importación – exportación.
          td Resolución 000004 de enero 20 de 2021
        tr
          td 530
          td Declaración de equipaje, de dinero en efectivo y títulos representativos en dinero – viajeros.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 532
          td Declaración de ingreso - salida dinero en efectivo.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 534
          td Declaración de ingreso - salida de títulos representativos de dinero por usuarios diferentes a viajeros.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 536
          td  Declaración de cambio simplificada por compra y venta profesional de divisas y cheques de viajero en zonas de frontera.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 538
          td Declaración de viajeros de San Andrés, Providencia y Santa Catalina.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 540
          td Declaración  consolidada de pagos (para los intermediarios de tráfico postal y envíos urgentes).
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 550
          td Factura de nacionalización.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 560
          td Declaración andina del valor.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 630
          td Factura de exportación.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 640
          td Certificado al proveedor – CP.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 650
          td Declaración de tránsito aduanero y/o cabotaje.
          td Resolución 000004 de enero 20 de 2021
        tr
          td 660
          td Continuación de viaje.
          td Resolución 000004 de enero 20 de 2021.
        tr
          td 690
          td Recibo oficial de pago tributos aduaneros y sanciones cambiarias.
          td Resolución 000004 de enero 20 de 2021.
    .row.justify-content-center.mb-5
      .col-lg-8
        .row.align-items-center
          .col-auto
            figure
              img(src='@/assets/curso/tema1/img8.svg', style="width: 200px").m-auto
          .col
            p En cuanto a los impuestos de orden departamental y municipal, se hace necesario consultar en cada caso particular la forma, los formatos, los calendarios tributarios, entre otros aspectos que se deben tener muy en cuenta para cumplir con estos compromisos tributarios.
    .separador.mb-5
    #t_1_5
    .titulo-segundo.color-secundario
      h2 1.5 Condiciones de liquidación
    p.mb-5 #[span.txt-deco1 Actualmente en Colombia los impuestos se presentan y se pagan mediante una auto-declaración.] Para el caso en concreto del impuesto de renta y complementarios, la DIAN es la encargada de verificar dicha liquidación, incluso actualmente para el caso de las personas naturales, sean estos trabajadores por cuenta propia, empleados, prestadores de servicios, entre otros, con base en los reportes de información exógena que realizan las personas jurídicas durante los primeros meses del año, la DIAN está enviando a los contribuyentes, una información provisional para que sean tenidas en cuenta a la hora de la presentación de sus declaraciones.
    .row.align-items-center.mb-5
      .col-lg-3
        figure.mb-4.mb-lg-0
          img(src='@/assets/curso/tema1/img4.png', style="width: 450px").m-auto
      .col-lg-9
        p.mb-0 Adicionalmente la DIAN al obtener esta información exógena, está en condiciones de objetar datos como ingresos, costos, o gastos de las auto declaraciones de los contribuyentes persona natural o jurídica, como también de así considerarlo, iniciar procesos de investigación administrativa, si así lo estima pertinente.
    .row.bg-color1.mb-5
      .col-12.p-5
        h3 Obligaciones
        p.mb-5 Son muchas las obligaciones o responsabilidades que se asumen cuando se crea una micro o pequeña empresa, existen responsabilidades tanto al interior de la compañía, de tipo tributario, ante terceros sean estos el estado, los proveedores, los clientes, los empleados, entre otros. La idea a es resaltar los compromisos más relevantes para nuestras empresas:
        .tarjeta.tarjeta--azul.p-4
          SlyderA
            .row.justify-content-center
              .col-11
                .p-5
                  .row.align-items-center
                    .col-lg-6.mb-4.mb-lg-0
                      h3.mb-4 Obligaciones con los socios o accionistas según el tipo de empresa:
                      .row.align-items-start.mb-3
                        .col-auto
                          figure
                            img(src='@/assets/curso/tema1/img13.svg', style="width: 30px").m-auto
                        .col
                          p.mb-0 Realizar la reunión de asamblea general ordinaria de accionistas o junta de socios según el caso. Para estas sesiones de conformidad con lo que establece el código del comercio el plazo máximo para la realización de las mismas es el 31 de marzo de cada año. Allí se debe detallar información surtida del periodo gravable inmediatamente anterior, a corte 31 de diciembre.
                      .row.align-items-start.mb-3
                        .col-auto
                          figure
                            img(src='@/assets/curso/tema1/img14.svg', style="width: 30px").m-auto
                        .col
                          p.mb-0 Registrar los estados financieros en la Cámara de Comercio correspondiente a más tardar el 31 de marzo de cada año.
                      .row.align-items-start
                        .col-auto
                          figure
                            img(src='@/assets/curso/tema1/img15.svg', style="width: 30px").m-auto
                        .col
                          p.mb-0 Renovar la matrícula mercantil igualmente en la Cámara correspondiente a más tardar el 31 de marzo.
                    .col-lg-6
                      figure
                        img(src='@/assets/curso/tema1/img10.svg', style="width: 450px").m-auto
            .row.justify-content-center
              .col-11
                .p-5
                  .row.align-items-center
                    .col-lg-6
                      h3.mb-4 Obligaciones de tipo tributario:
                      .row.align-items-start.mb-3
                        .col-auto
                          figure
                            img(src='@/assets/curso/tema1/img13.svg', style="width: 30px").m-auto
                        .col
                          p.mb-0 Declarar y pagar de manera oportuna según el caso las declaraciones tributarias a que hubiere lugar, entre ellas tenemos: renta, IVA, industria y comercio, y las demás a que pueda estar obligado según el tipo de sociedad, sector, etc.
                      .row.align-items-start
                        .col-auto
                          figure
                            img(src='@/assets/curso/tema1/img14.svg', style="width: 30px").m-auto
                        .col
                          p.mb-0 Presentar la información exigida de índole tributario a la Dian, en los formatos correspondientes (medios magnéticos).
                    .col-lg-6
                      figure
                        img(src='@/assets/curso/tema1/img11.svg', style="width: 450px").m-auto
            .row.justify-content-center
              .col-11
                .p-5
                  .row.align-items-center
                    .col-lg-6
                      h3.mb-4 Obligaciones laborales:
                      .row.align-items-start.mb-3
                        .col-auto
                          figure
                            img(src='@/assets/curso/tema1/img13.svg', style="width: 30px").m-auto
                        .col
                          p.mb-0 Liquidar y realizar los pagos a sus empleados por medio de la nómina electrónica.
                      .row.align-items-start
                        .col-auto
                          figure
                            img(src='@/assets/curso/tema1/img14.svg', style="width: 30px").m-auto
                        .col
                          p.mb-0 Realizar los pagos correspondientes por cada uno de sus empleados, de manera oportuna al sistema de seguridad social en Colombia. Recordemos que la UGPP es la entidad y autoridad encargada por parte del gobierno nacional para verificar que las empresas cumplan con dicha obligación.
                    .col-lg-6
                      figure
                        img(src='@/assets/curso/tema1/img12.svg', style="width: 450px").m-auto
    .row.bg-color3.mb-5
      .col-12.p-5
        h3 Contenido de las liquidaciones
        p.mb-5 Definir un estándar de la información que deben contener las liquidaciones de las declaraciones tributarias que deben presentar las micro y pequeñas empresas es muy complicado, especialmente por la multiplicidad de declaraciones que posiblemente deban presentar. Sin embargo, lo que sí se puede es detallar a nivel general la información más común, que es solicitada en estos casos. A continuación, se visualizan los siguientes:
        .tarjeta.tarjeta--azul.p-4
          SlyderA
            .row.justify-content-center
              .col-11
                .p-5
                  .row.align-items-center
                    .col-lg-6
                      h3 Soportes para los activos:
                      p.mb-5 En cuanto a los activos que se declaren en los compromisos tributarios de nuestra empresa, debemos contar con el documento idóneo para determinar la propiedad del bien y a su vez nos sirva para determinar el costo fiscal por el que se declara. A continuación, relacionamos una lista general dependiendo de los activos:
                      ul.lista-ul
                        li 
                          i.fas.fa-check(style="color: #EF9F14")
                          | Certificado de inversiones.
                        li 
                          i.fas.fa-check(style="color: #EF9F14")
                          | Facturas de compra de los activos. (maquinaria y equipos, equipos de cómputo)
                        li 
                          i.fas.fa-check(style="color: #EF9F14")
                          | Extractos bancarios.
                        li 
                          i.fas.fa-check(style="color: #EF9F14")
                          | Recibos de pago predial de bienes raíces de propiedad de la empresa.
                        li 
                          i.fas.fa-check(style="color: #EF9F14")
                          | Recibo de pago del impuesto de vehículos de propiedad de la empresa.
                        li 
                          i.fas.fa-check(style="color: #EF9F14")
                          | Certificados de avalúos técnicos.
                        li 
                          i.fas.fa-check(style="color: #EF9F14")
                          | Anexos de la declaración presentada el año inmediatamente anterior.
                    .col-lg-6
                      figure
                        img(src='@/assets/curso/tema1/img16.svg', style="width: 450px").m-auto
            .row.justify-content-center
              .col-11
                .p-5
                  .row.align-items-center
                    .col-lg-6
                      h3 Soportes para los pasivos:
                      p En cuanto a los pasivos que se detallan en las declaraciones tributarias de nuestra empresa, debemos tenerlos debidamente soportados. Por ejemplo, si tenemos créditos con entidades financieras, se debe contar con el extracto bancario que respalde el saldo. Los créditos con terceros particulares, se debe tener el documento soporte con fecha cierta.
                    .col-lg-6
                      figure
                        img(src='@/assets/curso/tema1/img17.svg', style="width: 450px").m-auto
            .row.justify-content-center
              .col-11
                .p-5
                  .row.align-items-center
                    .col-lg-6
                      h3 Soportes para los ingresos:
                      p Prácticamente es el ítem que ante la Dian es menos complicado soportar, sin embargo, lo ideal es contar con las facturas de venta, contratos que dieron origen a estos ingresos y demás documentos que nos permiten demostrar el origen de nuestros recursos. La contabilidad de nuestras empresas, a su vez, representa una prueba importante para evidenciar los ingresos.
                    .col-lg-6
                      figure
                        img(src='@/assets/curso/tema1/img18.svg', style="width: 450px").m-auto
            .row.justify-content-center
              .col-11
                .p-5
                  .row.align-items-center
                    .col-lg-6
                      h3 Soportes para costos y gastos:
                      p En este caso, contrario a lo manifestado en los ingresos, en los costos y gastos que declare la compañía, es donde la DIAN es muy exigente, por consiguiente, estos valores deben estar claramente soportados con una factura, o para el caso en que la proveedora que vende el producto o servicio, no esté obligada a facturar, allí procede el documento equivalente como soporte. El estatuto tributario en su artículo 771-2, señala los requisitos que debe cumplir la factura para que proceda legalmente como costo o gasto fiscalmente.
                    .col-lg-6
                      figure
                        img(src='@/assets/curso/tema1/img19.svg', style="width: 450px").m-auto
    p Adicionalmente se deben revisar otras normas procedentes que regulan los pagos que se realicen por fuera del sector financiero, es decir, los pagos en efectivo se encuentran limitados hasta ciertos porcentajes de los ingresos para que no sean rechazados como deducibles en la declaración de renta de las micro y pequeñas empresas.

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    modal1: false,
    modal2: false,
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>

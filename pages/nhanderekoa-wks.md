---
standalone: true
title: Nhanderekoa WKS
slug: nhanderekoa-wks
projeto: ''
pageSettings:
  language: en
  link_pt_br: '#'
  link_en: '#'
  link_es: '#'
  animations: enable_all
  direction: left
  seoTitle: ''
  seoDescription: ''
  seoKeywords: []
  seoImage: ''
pageTheme:
  primaryColor: ''
  secondaryColor: '#4daf4b'
  highlightColor: '#ffffff'
  auxiliaryColor: '#616161'
  displayFont: ''
  textFont: ''
  spacingPatterns:
    - name: Default
      mobile: 10px
      tablet: 10px
      desktop: 10px
pageInclude: null
modules:
  - type: MapBox
    style: mapbox://styles/studio-autonoma/cmsz20c6j009y01s0c0zx2bbz
    token: pk.eyJ1Ijoic3R1ZGlvLWF1dG9ub21hIiwiYSI6ImNtY3V2d3dtMTA0ZXgycnB4OW01cjlqb2QifQ.3NMaRt1maLlqTv 6nlVqVHA
    centerLng: '-46.766'
    centerLat: '-23.462'
    zoom: '13'
    bearing: '0'
    pitch: '0'
    layers: ti-jaragua
    columnAlign: left
    floatingText: false
    views:
      - id: mapview_1
        centerLng: '-46.677'
        centerLat: '-23.520'
        zoom: '9.64'
        mobileZoom: '5'
        duration: '2000'
        bearing: '0'
        pitch: '0'
        layers: |-
          ti-jaragua
          pateo-collegio
          capela-barueri
          exploracao-ouro-sp
        title: ''
        notes: ''
        items: []
      - id: mapview_2
        centerLng: '-46.633'
        centerLat: '-23.548'
        zoom: '16.39'
        mobileZoom: '5'
        duration: '2000'
        bearing: '0'
        pitch: '0'
        layers: pateo-collegio-area
        title: ''
        notes: ''
        items: []
components:
  - type: Group
    id: part_1_nhanderekoa
    shortTitle: part 1 nhanderekoa
    longTitle: Nhanderekoa
    description: cover of nhanderekoa's narrative
    showInMenu: true
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Custom
    customBgColor: '#23cd5685'
    backgroundMedia:
      - type: backgroundVideo
        videoSrc: /uploads/ndk_video_01_jaraguapeak.mp4
    overlay: dark
    components:
      - type: ColumnSticky
        txtColor: ''
        bgColor: ''
        paddingTop: false
        paddingBottom: false
        layout: text-bigger
        title: NHANDEREKOA
        components:
          - type: Spacer
            desktop: 800px
            tablet: 800px
            mobile: 400px
          - type: Text
            hasDropCap: false
            content: '### cartographies of Guarani territorial resistance and environmental reparation in the Jaraguá Indigenous Territory'
          - type: Spacer
            desktop: 800px
            tablet: 800px
            mobile: 400px
          - type: Text
            hasDropCap: false
            content: |-
              ###### After a cycle of historic mobilizations that took over São Paulo — Indigenous Territory — between 2013 and 2025, the Jaraguá Indigenous Territory was finally recognized as an ancestral Guarani territory.

              ###### Produced in collaboration with xeramõi and xejaryi, xondaros and xondarias, teachers, leaders, and Guarani activists, this platform presents a cartography of the current configuration of the Jaraguá Indigenous Territory at the moment of its physical demarcation, in September 2025.

              ###### Combining geospatial data analysis, participatory cartographies, interviews, and archival documentation, it traces a historical overview of the spatial practices of Guarani communities for the defense, care, and reparation of the Jaraguá forests.
          - type: Spacer
            desktop: 200px
            tablet: 200px
            mobile: 100px
  - type: Group
    id: part_1_text_1
    shortTitle: part 1 – text 1
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                The Guarani Jaraguá Indigenous Territory preserves the last fragments of Atlantic Forest in the city of São Paulo, one of the most devastated biomes in Brazil since European colonization.

                Beyond being a forest reserve of fundamental environmental and climatic importance for the São Paulo metropolis, where green areas are notoriously scarce, Jaraguá is a territory of immense spiritual and cultural value for the Indigenous communities that have lived there since time immemorial.

                Ka'aguy — the woods, the forest — is a landscape saturated with history and memory, the living heritage of the (human and non-human) ancestors of the Guarani people.
            - type: ImageBlock
              wideImage: true
              src: /uploads/NDK_img_jaraguapeak_stillvideo.jpg
              alt: ''
              description: Pico do Jaraguá (Jaraguá Peak) in São Paulo, Guarani Indigenous Territory.
        column2:
          components:
            - type: Spacer
              desktop: 200px
              tablet: 200px
              mobile: 100px
            - type: Pullquote
              content: The xeramoi always say that the elements of Guarani culture are embedded precisely in the ka'aguy, “the woods,” “the forest.” For us, ka'aguy is like our older brother, because the forest makes our way of life happen in the right way, because all the teachings are there.
              txtColor: ''
              bgColor: ''
              byline: Jurandir Tupã Jekupe Mirim
  - type: Group
    id: part_1_text_2
    shortTitle: part 1 - text 2
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Custom
    customBgColor: '#11d4146b'
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/ndk_placeholder_map1.png
    overlay: dark
    components:
      - type: Column
        paddingTop: false
        paddingBottom: false
        components:
          - type: Text
            hasDropCap: false
            content: |-
              ### JARAGUÁ INDIGENOUS TERRITORY

              The Jaraguá Indigenous Territory is a territory located in the city of São Paulo, traditionally inhabited by the Guarani Mbya people. The area recognized and demarcated by the Brazilian State covers 532 hectares, most of which remains covered by Atlantic Forest. The Jaraguá Indigenous Territory currently comprises nine Tekoas (villages).
          - type: Spacer
            desktop: 600px
            tablet: 600px
            mobile: 300px
          - type: InnerColumns
            column1:
              components:
                - type: Text
                  hasDropCap: false
                  content: |-
                    ###### TEKOA YTU

                    ###### territorial recovery and founding: 1960s

                    One of the oldest tekoas, Tekoa Ytu, “Waterfall Village”, was founded by the family of Joaquim Augusto Martim and Jandira Augusto Martim, the first Indian Chief of the Jaraguá Indigenous Territory. Its name refers to the Ribeirão das Lavras stream, which reaches the Tekoa by way of a small waterfall. Covering a perimeter of about 1.8 hectares, it was demarcated in 1987.

                    ###### TEKOA ITAKUPE

                    ###### territorial recovery and founding: 2005

                    Situated at the northern edge of the Jaraguá Indigenous Territory, the area where Tekoa Itakupe stands has been used by Guarani communities since the first territorial recoveries in the 1950s and 1960s. Founded in 2014, it is today made up of three housing clusters. Because it is located on the other side of Pico do Jaraguá (Jaraguá Peak), near its rock formations, it was named Itakupe, which can be translated as “behind the rock.”

                    ###### TEKOA ITAENDY

                    ###### territorial recovery and founding: 2017

                    Since its territorial recovery in 2017, Tekoa Itaendy, “yellow stone village,” has been promoting biodiversity maintenance practices such as reforestation with native species, the planting of swidden gardens with traditional foods, as well as the reintroduction and breeding of native bee species.

                    ###### TEKOA PINDÓ MIRIM

                    ###### territorial recovery and founding: 2023

                    One of the most recent tekoas in the Indigenous Territory, Pindó Mirim was recovered in 2023. Situated at the northwestern edge of the demarcated area, the community has been carrying out substantial environmental reparation work, focused on regenerating Atlantic Forest areas affected by the construction of the ring road Rodoanel and eucalyptus plantations. Notably, it has reforested with more than 1,500 native tree seedlings and 300 fruit tree seedlings.

                    ###### TEKOA KA’AGUY MIRIM

                    ###### territorial recovery and founding: 2024

                    Tekoa Ka’aguy Mirim is another territorial recovery adjacent to Tekoa Pyau. Named “small forest,” it sits at the edge of the Indigenous Territory, between the Bandeirantes Highway and Rua Antônio Cardoso Nogueira. The tekoa is regarded by its residents as an important site for the care of native medicinal species found there, a motivation that drove the recovery of the area.
            column2:
              components:
                - type: Text
                  hasDropCap: false
                  content: |-
                    ###### TEKOA PYAU

                    ###### territorial recovery and founding: 1990s

                    Tekoa Pyau, translated as “new village”, is the second tekoa in the historical process of territorial recovery of the Indigenous Territory. Today it is the most densely populated community in the Indigenous Territory. The tekoa is hemmed in by the Bandeirantes Highway and Rua Comendador de Matos, infrastructures that block its territorial continuity and have historically affected areas used for gathering, hunting, and cultivation.

                    ###### TEKOA ITAWERA

                    ###### territorial recovery and founding: 2014

                    Founded by Indian Chief Ara Poty (Maria) in 2014, Tekoa Itawera recovered an area previously used as a waste dumping site. Today, the community is dedicated to environmental and cultural recovery, through actions such as reforestation with native species, the cultivation of traditional foods like Guarani corn, as well as extensive craftwork. The tekoa’s name can be translated as “shining stone.”

                    ###### TEKOA YVY PORÃ

                    ###### territorial recovery and founding: 2018

                    Like Itawera, Yvy Porã was established in an area formerly used for urban waste disposal, at the foot of the forests of Pico do Jaraguá (Jaraguá Peak). Over the years, the tekoa has become an important reference point for ecological practices of clean-up, recovery, and maintenance of the Atlantic Forest. Yvy Porã, translated as “good land” or “beautiful land,” is also a reference for the recovery of various native bee species, such as the jate’i (jataí), considered sacred.

                    ###### TEKOA MIRIM

                    ###### territorial recovery and founding: 2023

                    Tekoa Mirim, meaning “small village,” is located next to Tekoa Pyau. Like other housing clusters, its residents have developed various practices of care and reparation of the territory. Notable is the planting of native, fruit, and vegetable seedlings along the path bordering the Bandeirantes Highway, connecting Tekoa Pyau to Tekoa Mirim and Ka’aguy Mirim.
  - type: Group
    id: part_1_text_3
    shortTitle: part 1 - text 3
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: VideoEmbed
              wideVideo: false
              videoUrl: https://player.vimeo.com/video/1106060903?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479
              videoCaption: Excerpt from the interview with Jurandir Tupã Jekupe Mirim on the meaning of Ka'aguy (forest) for Guarani culture.
            - type: Text
              hasDropCap: false
              content: |-
                Nhanderekoa – “the place where we live,” “the place where our way of life happens,” “where our culture lives” — is the title given to these cartographies and mappings. 

                Nhanderekoa expresses how the territory of Jaraguá, and its animals, plants, and spirits, are an integral part of how the Guarani understand their ways of dwelling and living, with the forest as an extension of a home shared between human and non-human beings within networks of care and reciprocity.

                For decades, Guarani communities have been resisting and fighting for the recognition of their ancestral lands and for the preservation of their sacred forests in Jaraguá.
        column2:
          components:
            - type: Pullquote
              content: “For us, the forest has an intelligence, everything works in a way that one thing connects to another, the animals matter to the ka'aguy and to us, the trees, the herbs... everything is connected. For us it is not simply the forest. It is our brother, a member of our people. As if they were connected spirits, one depending on the other.”
              txtColor: ''
              bgColor: ''
              byline: Jurandir Tupã Jekupe Mirim
  - type: Group
    id: part_1_text_4
    shortTitle: part 1 – text 4
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Spacer
              desktop: 300px
              tablet: 300px
              mobile: 150px
            - type: Gallery
              description: Participatory cartography in the Jaraguá Indigenous Territory
              uniqid: image_gallery_block
              images:
                - image: /uploads/ndk_img_mapacanvas_01.jpg
                  caption: 'Photo: Laura Pappalardo'
                - image: /uploads/ndk_img_mapacanvas_02.jpg
                  caption: 'Photo: Laura Pappalardo'
                - image: /uploads/ndk_img_mapacanvas_04.jpg
                  caption: 'Photo: Laura Pappalardo'
        column2:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                Tracing concrete knowledge and lived experience across the territory, the map identifies areas of fundamental importance for Guarani dwelling — such as sacred sites, traditional paths, protected areas, forest-reparation areas, and native-species recovery areas — that are not recorded in official databases and, for that reason, tend to be rendered invisible by public policy.

                Unlike the maps produced by the State, where the Indigenous Territory appears as a large, empty green space, this map shows a densely inhabited land, shaped through the practices of nhandereko, the Guarani way of dwelling.

                By spatializing these processes, the map sheds light on practices that are often made invisible, especially the everyday care work of the women who put down deep roots so that the Jaraguá Indigenous Territory can grow strong.
            - type: ImageBlock
              wideImage: true
              src: /uploads/ndk_250815_cuidado_R17_crop.jpg
              alt: ''
              description: Practices of Care and Reparation in the Jaraguá Indigenous Territory.
      - type: Slider
        slides:
          - image: /uploads/ndk_folder1.jpg
            caption: Nhanderekoa's folder map
          - image: /uploads/ndk_folder3.jpg
            caption: ''
          - image: /uploads/ndk_folder4.jpg
            caption: ''
      - type: Spacer
        desktop: 100px
        tablet: 100px
        mobile: 50px
  - type: Group
    id: part_2_demarcation
    shortTitle: part 2 - demarcation
    longTitle: Return to Democracy & Demarcation of Tekoa Ytu
    description: ''
    showInMenu: true
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Custom
    customBgColor: '#00b344a1'
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/ndk_img_14_constituinte.jpg
    overlay: dark
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                # Part II

                # Return to Democracy & Demarcation of Tekoa Ytu

                # (1984 – 1989)
            - type: Spacer
              desktop: 100px
              tablet: 100px
              mobile: 50px
        column2:
          components: []
  - type: Group
    id: part_2_text_1
    shortTitle: part 2 – text 1
    longTitle: ''
    description: ''
    showInMenu: false
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: ImageBlock
              wideImage: false
              src: /uploads/ndk_img_16_logo_mata_atlantica_unesco.jpg
              alt: ''
              description: UNESCO Biosphere Reserve Seal
            - type: Spacer
              desktop: 600px
              tablet: 600px
              mobile: 300px
            - type: ChartBar
              chartTitle: Native vegetation suppression in the surroundings of Jaraguá
              chartNotes: Advancement of urban occupation over vegetation cover in the surroundings of the Jaraguá Indigenous Land
              chartBars:
                - label: Aerial photographs from 1954
                  color: '#0b7f22ff'
                  number: 60
                  numberPercent: null
                - label: Sattelite imagery from 1990
                  color: '#294fa8ff'
                  number: 75
                  numberPercent: null
                - label: Sattelite imagery from 2010
                  color: '#87af3cff'
                  number: 88
                  numberPercent: null
        column2:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                At the same time, between the assassinations of Marçal de Souza and Chico Mendes in 1983-1984, and the United Nations’ international ECO-92 summit held in Rio de Janeiro in 1992, the environmental agenda became consolidated internationally and in Brazil.

                In 1994, Jaraguá State Park was recognized by UNESCO as a World Heritage Site, in the Biosphere Reserve category, becoming part of the São Paulo Green Belt.

                As with the creation of the State Park in 1961, such environmental protection measures often conflict with the Guarani communities’ right to their ancestral territory, preventing them from making use of the natural resources of the forests within the boundaries of the Park, which today is entirely fenced off.
            - type: ImageBlock
              wideImage: true
              src: /uploads/ndk_img_30_cinturao_verde.jpg
              alt: ''
              description: Map of the northern area of the São Paulo Green Belt. The forests of the Jaraguá Indigenous Territory are the best preserved in the belt.
            - type: Compare
              imageLeft: /uploads/ndk_jaragua_1954.jpg
              imageRight: /uploads/ndk_jaragua_2024.jpg
              caption: Aerial images from 1954 and 2024, evidencing the reduction of vegetation cover in the surroundings of Jaraguá, associated with the expansion of the metropolitan urban grid.
      - type: Column
        paddingTop: false
        paddingBottom: false
        components:
          - type: HtmlEmbed
            wideHtml: false
            htmlCode: <iframe title="Topo model Jaraguá" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/b0cfe274d6e44254a641aea67f2e6338/embed"> </iframe>
            htmlCaption: 3D model of Jaraguá Peak (Pico do Jaraguá) and surrounding area, present day.
      - type: Columns
        paddingTop: false
        paddingBottom: false
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: ChartPercentage
              chartPercentageTitle: Proportions between the areas of the Jaraguá Indigenous Land and Jaraguá State Park
              chartPercentageNotes: 'Total area considering the State Park and the Indigenous Land: 716.18 ha'
              chartPercentageValues:
                - label: Jaraguá Indigenous Land area without overlap with the State Park
                  color: '#258839ff'
                  number: 31.3
                - label: Jaraguá State Park area overlapping the Indigenous Land area
                  color: '#58a793ff'
                  number: 43
                - label: Jaraguá State Park exclusive area
                  color: '#cec58dff'
                  number: 25.7
                - label: Jaraguá State Park exclusive area 2
                  color: '#aa2c2cff'
                  number: 40
        column2:
          components:
            - type: BigNumbers
              alignment: caption-bottom
              items:
                - number: 492ha
                  caption: Jaraguá State Park area (2024)
                - number: 532ha
                  caption: Jaraguá Indigenous Land area (2024)
                - number: 308ha
                  caption: State park area overlapping the Indigenous Land
  - type: Map
    id: map_1
    shortTitle: map 1 - colonial heritage
    longTitle: Colonial Heritage
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    bgColor: ''
    components:
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: mapview_1
      - type: Spacer
        desktop: 800px
        tablet: 800px
        mobile: 400px
      - type: MapView
        txtColor: ''
        bgColor: ''
        mapView: mapview_2
      - type: Spacer
        desktop: 800px
        tablet: 800px
        mobile: 400px
    columnAlign: left
    floatingText: false
---

# ViaggiaFacile - Schema ER 
Maksym Lebediuk • Aldo Li Rosi • Vincenzo Scarso



```mermaid 
erDiagram 
    Utenti ||--o{ Viaggi : "organizza" 
    Viaggi ||--o{ Itinerari : "si_compone_di" 
    Viaggi ||--o{ Voli : "include_volo" 
    Viaggi ||--o{ Hotel : "prevede_soggiorno_in" 
    Viaggi ||--o{ Trasporti : "utilizza_mezzo" 
    Viaggi ||--o{ Attivita : "programma" 
    Viaggi ||--o{ Spese : "comporta_spesa" 
    Destinazioni ||--o{ Itinerari : "rappresenta_tappa_di" 
    Destinazioni ||--o{ Rischi_Paesi : "è_soggetta_a_rischio" 
 
    Utenti { 
    } 
 
    Destinazioni { 
    } 
 
    Viaggi { 
    } 
 
    Itinerari { 
    } 
 
    Voli { 
    } 
 
    Hotel { 
    } 
 
    Trasporti { 
    } 
 
    Attivita { 
    } 
 
    Spese { 
    } 
 
    Rischi_Paesi { 
    } 
``` 

---

[Preview su mermaid](https://mermaid.ai/play?utm_source=ai_live_editor&utm_medium=share#pako:eNp1k82Om0AMx18F-cyuIAmBcKu6h_ZQqerHHiokZAUvGQnGyDNELWzep-_RF-vw0aWRgBPj39_2-G9ND2cuCFIgeVJYCtZepj33fbekrfJeXx8euPeeHSuVl3oZsJSoVddhBrN0hrP0o1WaBGVSG5WfuW5YU16ojYxnriax0ueqLSi_csUb2g9sqRrFjdCVnNiwwyyac6U3kr4JmobFTl1aq6rh_nlNXbfV55216qoszq14cKbeGvlrQ4ZG5TirWMyNCy3yJzLOFewU6w2fBBs3kHGeY27dP_5v11r6F2XOF5V_RjJThT-_RyvIugqYy4jn6e422s_H20Lu6q_wedoVsgyxljbsdSU-7XAFLHtagW8bWWHTAlbAnUsLBx9KUQWkVlryoSapcThCPygysBeqKYPB1oJesK1sBpm-ubQG9Q_m-l-mcFteIH3ByrhT2xRoaX5Hb1EhXZC851ZbSMP9WAPSHn5CGoWP-ziMdkEUBHGw2518-OU0Jxc-Jvs4OYanIE6Cw82HbuwaPCaHUxgnSRQcI4figw9UKMvyaXrG42u-_QWV6zXk)

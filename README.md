# Diagrama-de-Gantt-P4
En este podremos clasificarnos las tareas del proyecto en cuanto fecha de inicio, fecha de finalización y dividirnos el trabajo de manera eficiente.

```mermaid
gantt
    title Proyecto 4
    dateFormat YYYY-MM-DD

    %% Tarea fantasma para definir el inicio
    "" : milestone, start1, 2025-02-03, 3d

    section Gestión del proyecto
    Acta de constitución (Starlyn)                       :active,  des1, 2025-02-17, 1d
    Diagrama de Gantt (Starlyn)                          :active,  des2, 2025-02-20, 1d
    Gestor de contenidos (Starlyn)                      :active,         des3, 2025-02-21, 4d
    PLE (Starlyn, Gianpiero, Herty)                                       :active,         des4, 2025-02-24, 1d

    section Equipos informaticos
    Componentes y recanvios (Herty)                                           :active,         des5, 2025-02-24, 2d
    Análisis de la BIOS (Starlyn, Gianpiero y Herty)                                               :active,         des6, 2025-02-19, 39d
    Protocolos de reparación de averías I averías en el hardware (Starlyn, Herty)       :active,         des7, 2025-02-25, 3d
    Prevención de riesgos - Equipos informáticos (Gianpiero, Herty)                     :active,         des8, 2025-02-27, 2d
    Gestión de residuos - Equipos informáticos (Gianpiero, Herty)                       :active,         des9, 2025-02-28, 2d

    section Redes
    Redes inalámbricas (Starlyn)                                               :active,        des10, 2025-03-03, 1d
    Protocolos de reparación de averías II averías en la red   (Starlyn, Herty)       :active,        des11, 2025-03-04, 3d
    Prevención de riesgos - Redes  (Gianpiero, Herty)                                     :active,        des12, 2025-03-05, 2d
    Gestión de residuos - Redes (Gianpiero, Herty)                                      :active,        des13, 2025-03-06, 2d

    section Sistema operativo y software                              
    Sistemas operativos (Starlyn, Gianpiero, Herty)                                                :active,         des14, 2025-03-03, 2d
    Aplicaciones (Starlyn, Gianpiero, Herty)                                                       :active,         des15, 2025-03-05, 2d
                
    section La web
    El servicio FTP (Starlyn, Gianpiero, Herty)                                                    :active,         des16, 2025-03-10, 2d
    La web (Starlyn, Gianpiero, Herty)                                                            :active,         des17, 2025-03-12, 3d
    Base de datos (Starlyn, Gianpiero y Herty)                                                      :active,         des18, 2025-03-11, 2d
    Sistema de tickets (Starlyn, Herty)                                                 :active,         des19, 2025-03-15, 4d
    Vídeo tutoriales de reparación de averías (Starlyn, Gianpiero, Herty)                         :active,         des20, 2025-03-17, 5d
    Helpdesk (Gianpiero)                                                         :active,         des21, 2025-03-24, 5d

    section Recursos Humanos (RRHH) 
    CV en inglés (Starlyn, Gianpiero y Herty)                                                      :active,         des22, 2025-02-21, 4d
    Convenio colectivo (Starlyn, Gianpiero y Herty)                                                :active,         des23, 2025-02-24, 2d
    Plan de prevención de riesgos laborales (Gianpiero)                           :active,         des23, 2025-02-25, 2d
    Entrevista de trabajo (inglés) (Starlyn, Gianpiero, Herty)                                   :active,         des24, 2025-03-24, 5d

    section  Gestión documental 
    La memoria (Starlyn, Gianpiero, Herty)                                                         :active,    des25, 2025-02-17, 41d
    La presentación (Starlyn, Gianpiero, Herty)                                                  :active,  des26, 2025-03-18, 3d

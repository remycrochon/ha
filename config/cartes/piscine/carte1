type: grid
cards:
  - type: gauge
    entity: input_number.mem_temp_piscine
    min: 0
    max: 40
    severity:
      green: 27
      yellow: 0
      red: 30
    name: Temp Eau
    needle: true
  - type: gauge
    entity: sensor.vp2_temp_out
    max: 45
    name: T° Ext
    min: -10
    severity:
      green: 15
      yellow: -10
      red: 30
    needle: true
  - type: gauge
    entity: sensor.pression_filtre
    min: 0
    max: 2
    severity:
      green: 0
      yellow: 0.9
      red: 1
    name: P Filtre
    unit: B
    needle: true
  - type: gauge
    entity: sensor.ph_piscine_ph
    min: 6
    max: 9
    name: pH
    severity:
      green: 7.1
      yellow: 6
      red: 7.7
    needle: true
  - type: gauge
    entity: sensor.orp_piscine_orp
    min: 0
    name: ORP
    severity:
      green: 750
      yellow: 0
      red: 900
    needle: true
    max: 1009
  - type: gauge
    entity: sensor.e_fc
    min: 0
    max: 10
    name: Fc
    needle: true
  - type: gauge
    entity: input_number.temps_cartouche_chlore
    min: 0
    max: 70
    name: Cart Chlore
    severity:
      green: 0
      yellow: 30
      red: 60
    needle: true
  - type: gauge
    entity: sensor.pzem_pisc_puissance
    min: 0
    max: 900
    name: Puissance
    severity:
      green: 0
      yellow: 350
      red: 800
    needle: true
  - aspect_ratio: 1
    color: auto
    entity: pool_pump.next_run_schedule
    name: Tranche Horaire
    hold_action:
      action: more-info
    show_state: true
    type: custom:button-card
  - aspect_ratio: 1
    color: auto
    entity: binary_sensor.pool_pump_running
    name: Ppe Filtre
    hold_action:
      action: more-info
    show_last_changed: true
    show_state: true
    state:
      - styles:
          icon:
            - color: red
        value: 'off'
      - styles:
          icon:
            - color: green
        value: 'on'
    type: custom:button-card
  - aspect_ratio: 1
    color: auto
    entity: automation.piscine_injection_v2
    name: Injection pH
    hold_action:
      action: more-info
    show_last_changed: true
    show_state: true
    state:
      - styles:
          icon:
            - color: red
        value: 'off'
      - styles:
          icon:
            - color: green
        value: 'on'
    type: custom:button-card
  - aspect_ratio: 1
    color: auto
    entity: cover.volet_piscine
    name: Volet Piscine
    hold_action:
      action: more-info
    show_last_changed: true
    show_state: true
    confirmation:
      text: '[[[ return `Etes vous sur ${entity.attributes.friendly_name}?` ]]]'
    state:
      - styles:
          icon:
            - color: red
        value: open
      - styles:
          icon:
            - color: green
        value: closed
    type: custom:button-card
square: true


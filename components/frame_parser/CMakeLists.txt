idf_component_register(
    SRCS "frame_eapol_validator.c" "frame_output.c" "frame_parser.c"
    INCLUDE_DIRS "includes" "frame_types" "interface"
    PRIV_REQUIRES esp_event esp_wifi
)
set(app_src nmea_parser.c)
set(pre_req driver log)
idf_component_register(SRCS ${app_src}
                    INCLUDE_DIRS "."
                    REQUIRES ${pre_req})
project (epub2txt)

add_definitions (-DVERSION=\\"0.1.4\\")

add_executable (epub2txt main.c epub2txt.c
	klib_error.c klib_object.c klib_string.c klib_log.c klib_buffer.c
	klib_wstring.c klib_convertutf.c klib_getopt.c klib_getoptspec.c
	klib_list.c klib_path.c klib_xml.c sxmlc.c sxmlutils.c)

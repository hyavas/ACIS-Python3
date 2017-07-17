# Implemented Functonality

**Note:** Some class methods might be missing. Please see [CONTRIBUTING](CONTRIBUTING.md) file for details.

## Modeler

### Functions

* api_start_modeller (api_start_modeler)
* api_stop_modeller (api_stop_modeler)
* is_modeler_started
* api_set_dbl_option
* api_set_int_option
* api_set_str_option
* api_solid_block
* api_make_cuboid
* api_make_frustum
* api_make_prism
* api_make_pyramid
* api_make_sphere
* api_make_torus
* api_apply_transf
* api_remove_transf
* api_unite
* api_intersect
* api_subtract
* api_imprint
* api_sheet_from_ff
* api_boolean_chop_body

## Topology

### Classes

* ENTITY
* BODY
* LUMP
* SHELL
* SUBSHELL
* FACE
* EDGE
* COEDGE
* VERTEX
* WIRE

## Geometry

### Classes

* SURFACE
* CONE
* PLANE
* SPHERE
* SPLINE
* TORUS

## Geometric Atoms

### Classes

* SPAposition
* SPAtransf
* SPAmatrix
* SPAvector
* SPAunit_vector

## Geometric Operators

### Functions

* translate_transf

## Lists

### Classes

* ENTITY_LIST

## Query

### Functions

* get_owner_transf
* api_get_faces
* api_get_edges

## Save & Restore

### Classes

* FileInfo

### Functions

* api_save_entity_list
* api_set_file_info
* api_get_file_info
* api_save_version

## Sweeping

### Functions

* api_make_sweep_path
* api_sweep_with_options

### Classes / Enums

* sweep_bool_type
* sweep_options
* make_sweep_path_options

## Licensing

### Functions

* spa_unlock_products
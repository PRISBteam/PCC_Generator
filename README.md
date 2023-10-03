# PCC Generator tool
<p>
The code creates Combinatorial Discrete Cell Complexes and related measures based on the <a href="https://neper.info/" target="_blank"> Neper </a> output '*.tess' files of 2D/3D space tessellations.
</p>

Combinatorial (../combinatorial/): <br>
<p>
'number_of_cells' - numbers of 0-cells (first line), 1-cells (second line), 2-cells (third line) and 3-cells (fourth line) in the PCC <br>
'vertex_set' - a simple list of vertex IDs <br>
'edge_set'  - a list of edges represented as a couples of vertex IDs written in each line <br>
'face_set'  - a list of faces represented as a sets of vert IDs written in each line <br>
'grain_set'  - a list of grains represented as a set of vertex IDs written in each line <br>
</p>

Boundaries: <br>
<p>
'node_tboundaries' - 0-cells belonging to the tessellation geometric bounbdaries <br>
'edge_tboundaries' - 0-cells belonging to the tessellation geometric bounbdaries <br>
'face_tboundaries' - 0-cells belonging to the tessellation geometric bounbdaries <br>
'grain_tboundaries' - 0-cells belonging to the tessellation geometric bounbdaries <br>
</p>

Adjacency matrices (../algebraic/): <br>
<p>
'A0' - adjacency 0-cells x 0-cells  sparse matrix <br>
'D0' - diagonal degree matrix of 0-cells (contains number of neighbours for each 0-cell) <br>
'A1' - adjacency 1-cells x 1-cells sparse matrix\ <br>
'D1' - diagonal degree matrix of 1-cells (contains number of neighbours for each 1-cell) <br>
'A2' - adjacency 2-cells x 2-cells sparse matrix <br>
'D2' - diagonal degree matrix of 2-cells (contains number of neighbours for each 2-cell) <br>
'A3' - adjacency 3-cells x 3-cells sparse matrix <br>
'D3' - diagonal degree matrix of 3-cells (contains number of neighbours for each 3-cell) <br>
</p>

Incidence matrices(../algebraic/): <br>
<p>
'B1' - incidence 1-cells x 0-cells sparse matrix <br>
'B2' - incidence 2-cells x 1-cells sparse matrix <br>
'B3' - incidence 3-cells x 2-cells sparse matrix <br>
</p>

Coordinates (../coordinates/): <br>
<p>
'vertex_seeds' - vertices Cartesian coordinates from the initial tessellation of space <br>
'edge_barycenter_seeds' - edges Cartesian coordinates from the initial tessellation of space <br>
'face_barycenter_seeds' - faces Cartesian coordinates from the initial tessellation of space <br>
'volume_barycenter_seeds' - polyhedra Cartesian coordinates from the initial tessellation of space <br>
</p>

Measures (../measures/): <br>
<p>
'edge_lengths' - lengths of edges from the initial tessellation of space <br>
'face_areas' - areas of faces from the initial tessellation of space <br>
'grain_volumes' - areas of faces from the initial tessellation of space <br>
</p>

Other (../other/): <br>
<p>
'face_normals' - normal vector to each face in the initial tessellation of space <br>
</p>

Tessellation (../tessellation/): <br>
<p>
'initial_Neper_tessellation' - jpg figure with the initial tessellation of space <br>
'*.tess' - Neper (https://neper.info/) output file containing the initial tessellation of space <br>
</p>


Reference configurations (../design_vectors/): <br>
Random (../references/random/): <br>
<p>
'special_grains' - random based sequence of special grains (3-cells) in the PCC <br>
'special_faces' - random based sequence of special faces (2-cells) in the PCC <br>
'special_edges' - random based sequence of special edges (1-cells) in the PCC <br>
'special_nodes' - random based sequence of special nodes (0-cells) in the PCC <br>
</p>

S_max  (../references/Smax/): <br>
<p>
'special_grains' - maximum configuration entropy production principle (MEPP) based sequence of special grains (3-cells) in the PCC <br>
'special_faces' -  maximum configuration entropy production principle (MEPP) based sequence of special faces (2-cells) in the PCC <br>
'special_edges' -  maximum configuration entropy production principle (MEPP) based sequence of special edges (1-cells) in the PCC <br>
'special_nodes' -  maximum configuration entropy production principle (MEPP) based sequence of special nodes (0-cells) in the PCC <br>
</p>

S_min  (../references/S_min/): <br>
<p>
'special_grains' -  minimum configuration entropy production principle (MIEPP) based sequence of special grains (3-cells) in the PCC <br>
'special_faces' - minimum configuration entropy production principle (MIEPP) based sequence of special faces (2-cells) in the PCC <br>
'special_edges' - minimum configuration entropy production principle (MIEPP) based sequence of special edges (1-cells) in the PCC <br>
'special_nodes' - minimum configuration entropy production principle (MIEPP) based sequence of special nodes (0-cells) in the PCC <br>
</p>

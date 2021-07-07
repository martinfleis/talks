# *Urban morphology as an open reproducible data science*

 <CENTER>
    *Martin Fleischmann*
</CENTER>
<br>
<table>
    <col width="100%">
    <tr>
        <td>
            <CENTER>
                <a href="https://twitter.com/martinfleis">@martinfleis</a>
            </CENTER>
        </td>
    </tr>
    <tr>
        <td>
            <CENTER>
                <a href="https://martinfleischmann.net">martinfleischmann.net</a>
            </CENTER>
        </td>
    </tr>
</table>



#
## Urban Form

<CENTER>
    <span class='fragment'> *What does a city look like?*</span>
</CENTER>

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        "Physical structure and appearance of cities"
    </span>
</CENTER>

## What do we talk about...

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        ... when we talk about urban morphology?
    </span>
</CENTER>
<br />
<table>
    <col width="25%">
    <col width="25%">
    <col width="25%">
    <col width="25%">
    <tr>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    buildings
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    streets
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    plots
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    open spaces
                </span>
            </CENTER>
        </td>
    </tr>
</table>

## How can we describe it...

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        ... numerically?
    </span>
</CENTER>

## Urban morphometrics

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        "quantitative analysis of urban form"
    </span>
</CENTER>

<br />
<CENTER>
    <span class='fragment'>
        All about <span class='hlg'>measuring</span>.
    </span>
</CENTER>

## Measuring

<table>
    <col width="33%">
    <col width="33%">
    <col width="33%">
    <tr>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    dimension
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    shape
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    spatial distribution
                </span>
            </CENTER>
        </td>
    </tr>
    <tr>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    intensity
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    connectivity
                </span>
            </CENTER>
        </td>
        <td style="vertical-align:middle">
            <CENTER>
                <span class='fragment'>
                    diversity
                </span>
            </CENTER>
        </td>
    </tr>
</table>

## Why?

<CENTER>
    <span class='fragment'>
        Because we (finally) can!
    </span>
</CENTER>

## Data

<CENTER>
    <span class='fragment'>
        <img src="../fig/misc/osm.png" style="width:100%;vertical-align:middle;box-shadow:none">
    </span>
</CENTER>

#
## Tools
<table>
    <col width="33%">
    <col width="33%">
    <col width="33%">
    <tr>
        <td>
            <CENTER>
                <span class='fragment'>
                    GeoPandas
                </span>
            </CENTER>
        </td>
        <td>
            <CENTER>
                <span class='fragment'>
                    PySAL
                </span>
            </CENTER>
        </td>
        <td>
            <CENTER>
                <span class='fragment'>
                    momepy
                </span>
            </CENTER>
        </td>
    </tr>
</table>

## GeoPandas

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        GeoPandas is an open source project to add support for geographic data to pandas objects.
    </span>
</CENTER>
<br />
<CENTER>
    <span class='fragment'>
        <a href="https://geopandas.org">geopandas.org</a>
    </span>
</CENTER>

## PySAL

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        Python Spatial Analysis Library
    </span>
</CENTER>
<br />
<CENTER>
    <span class='fragment'>
        <a href="https://pysal.org">pysal.org</a>
    </span>
</CENTER>

## momepy

<CENTER>
    <span class='fragment' style='color:#3b6e8c'>
        Urban Morphology Measuring Toolkit
    </span>
</CENTER>
<br />
<CENTER>
    <span class='fragment'>
        <a href="https://momepy.org">momepy.org</a>
    </span>
</CENTER>

#
## Few examples

##

<table>
    <col width="50%">
    <col width="50%">
    <tr>
        <td>
            <CENTER>
                <img src="../fig/misc/momepy_lal.png" style="width:100%;vertical-align:middle;box-shadow:none">
                <SMALL>
                    longest axis length<br>
                    <span style='color:#3b6e8c'>dimension</span>
                </SMALL>
            </CENTER>
        </td>
        <td>
            <CENTER>
                <span class='fragment'>
                    <img src="../fig/misc/momepy_eri.png" style="width:100%;vertical-align:middle;box-shadow:none">
                    <SMALL>
                        equivalent rectangular index<br>
                        <span style='color:#3b6e8c'>shape</span>
                    </SMALL>
                </span>
            </CENTER>
        </td>
    </tr>
</table>

##

<table>
    <col width="50%">
    <col width="50%">
    <tr>
        <td>
            <CENTER>
                <img src="../fig/misc/momepy_ndis.png" style="width:100%;vertical-align:middle;box-shadow:none">
                <SMALL>
                    distance to neighbours<br>
                    <span style='color:#3b6e8c'>spatial distribution</span>
                </SMALL>
            </CENTER>
        </td>
        <td>
            <CENTER>
                <span class='fragment'>
                    <img src="../fig/misc/momepy_car.png" style="width:100%;vertical-align:middle;box-shadow:none">
                    <SMALL>
                        covered area ratio<br>
                        <span style='color:#3b6e8c'>intensity</span>
                    </SMALL>
                </span>
            </CENTER>
        </td>
    </tr>
</table>

##

<table>
    <col width="50%">
    <col width="50%">
    <tr>
        <td>
            <CENTER>
                <img src="../fig/misc/momepy_mca.png" style="width:100%;vertical-align:middle;box-shadow:none">
                <SMALL>
                    closeness centrality<br>
                    <span style='color:#3b6e8c'>connectivity</span>
                </SMALL>
            </CENTER>
        </td>
        <td>
            <CENTER>
                <span class='fragment'>
                    <img src="../fig/misc/momepy_div.png" style="width:100%;vertical-align:middle;box-shadow:none">
                    <SMALL>
                        Simpson's diversity of tessellation area<br>
                        <span style='color:#3b6e8c'>diversity</span>
                    </SMALL>
                </span>
            </CENTER>
        </td>
    </tr>
</table>

#
## Evolution of urban patterns

## 42 places, 6 historical periods

<CENTER>
    <img src="../fig/misc/gean_map.svg" style="width:100%;vertical-align:middle;box-shadow:none">
</CENTER>

## 400 m buffer

<CENTER>
    <img src="../fig/misc/gean_case_illustrations.png" style="width:70%;vertical-align:top;box-shadow:none">
</CENTER>

## Scale peaked in modernism

<CENTER>
    <img src="../fig/misc/gean_results_1.png" style="width:60%;vertical-align:top;box-shadow:none">
</CENTER>

## We forgot how to make a grid

<CENTER>
    <img src="../fig/misc/gean_results_4.png" style="width:60%;vertical-align:top;box-shadow:none">
</CENTER>

#
## Classification

## Detection of patterns

<CENTER>
    <img src="../2020_GeoPython_Online/figures/PRG_clusters.png" style="width:80%;vertical-align:top;box-shadow:none">
</CENTER>

<span class="pie">Prague</span>

## Spatial Signatures

<CENTER>
*A characterisation of space based on form and function designed to understand urban environments*
</CENTER>

## {data-transition="none" data-background-image="../fig/sp_sig/barcelona_signatures_and_buildings_background.png"
data-background-size="contain"}

<span class="pie">Barcelona</span>

## {data-transition="none" data-background-image="../fig/sp_sig/houston_medellin_background.png"
data-background-size="contain"}

<span class="pie">Houston | Medellin</span>

## {data-transition="none" data-background-image="../fig/sp_sig/singapore_dar_es_salaam_background.png"
data-background-size="contain"}

<span class="pie">Singapore | Dar es Salaam</span>

#
## Reproducible open science

<CENTER>
    <img src="../fig/misc/gh.png" style="width:80%;vertical-align:top;box-shadow:none">
</CENTER>

# *Urban morphology as an open reproducible data science*

 <CENTER>
    *Martin Fleischmann*
</CENTER>
<br>
<table>
    <col width="100%">
    <tr>
        <td>
            <CENTER>
                <a href="https://twitter.com/martinfleis">@martinfleis</a>
            </CENTER>
        </td>
    </tr>
    <tr>
        <td>
            <CENTER>
                <a href="https://martinfleischmann.net">martinfleischmann.net</a>
            </CENTER>
        </td>
    </tr>
</table>

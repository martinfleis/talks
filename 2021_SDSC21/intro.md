# *Spatial Signatures*

<CENTER>
    *Capturing the Structure of Cities with Data Science*
</CENTER>

<table>
    <col width="100%">
    <tr>
        <td>
            <CENTER>
                <a href="https://martinfleischmann.net/"><b>Martin Fleischmann</b></a>
            </CENTER>
        </td>
    </tr>
    <tr>
        <td>
            <CENTER>
                <a href="https://twitter.com/martinfleis">[`@martinfleis`]</b></a>
            </CENTER>
        </td>
    </tr>
</table>

<table>
    <col width="50%">
    <col width="50%">
    <tr>
        <td>
            <img src="fig/logo_liv.png" style="width:300px;vertical-align:middle;box-shadow:none">
        </td>
        <td>
            <img src="fig/logo_gdsl.png" style="width:300px;vertical-align:middle;box-shadow:none">
        </td>
    </tr>
</table>

#
## How we arrange "stuff" in cities matters...

<table>
    <col width="50%">
    <col width="50%">
    <tr>
        <td>
            <CENTER>
                <img src="fig/nyt_buildings_dc.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>

        <td>
            <CENTER>
                <img src="fig/nyt_buildings_mesa.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>
    </tr>
</table>

<span class='pie'>Source: *A map of every building in America* ([New York
    Times](https://www.nytimes.com/interactive/2018/10/12/us/map-of-every-building-in-the-united-states.html))</span>

##

... it matters *a lot*

<table>
    <col width="33%" height="50%">
    <col width="33%" height="50%">
    <col width="33%" height="50%">
    <tr>
        <td>
            <CENTER>
                <img src="fig/joue_density.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>

        <td>
            <CENTER>
                <img src="fig/cities_in_bad_shape.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>

        <td>
            <CENTER>
                <img src="fig/est_emissions.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>
    </tr>
    <tr class='fragment'>
        <td>
            <CENTER>
                <img src="fig/living_with_beauty.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>

        <td>
            <CENTER>
                <img src="fig/oecd_rethinking_sprawl.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>

        <td>
            <CENTER>
                <img src="fig/un_nua.png" style="width:100%;vertical-align:middle">
            </CENTER>
        </td>
    </tr>
</table>


#
## Urban Form

<CENTER>
    *What does it look like?*
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
        <img src="fig/osm.png" style="width:100%;vertical-align:middle;box-shadow:none">
    </span>
</CENTER>

## Tools
<table>
    <col width="25%">
    <col width="25%">
    <col width="25%">
    <col width="25%">
    <tr>
        <td>
            <CENTER>
                <span class='fragment'>
                    OSMnx
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
                    foot
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

## momepy

<CENTER class='fragment' >
    <span style='color:#3b6e8c'>
        Urban Morphology Measuring Toolkit
    </span>
    <small>
Member of a PySAL family
</small>
</CENTER>
<CENTER>
    <span class='fragment'>
        <a href="https://momepy.org">momepy.org</a> & <a href="https://pysal.org">pysal.org</a>
    </span>
</CENTER>
---
layout: page
permalink: /research/
title: research
description: 
nav: true
---

## mechanics & rheology of granular materials

Granular materials are ubiquitously found in nature and industry, being only the second most widely material in industry after water. Their occurence in nature ranges from sand and soil to large-scale geophysical phenomena such as earthquakes and landslides. Despite being compositionally very simple consisiting of hard frictional particles, these materials can deform in remarkably complex ways to applied stresses, often exhibiting both solid- and fluid-like characteristics. Currently, there is a lack of a well-defined theoretical foundation that can describe all their states of existence, and critically, the transitions between these states. My research has focused on bridging this gap by using discrete element simulations to both highlight particle-scale phenomena and provide continuum predictions of their mechanics and rheology, especially their transition between solid- and fluid-like states upon external stressing.

Using large-scale discrete element simulations, we highlighted that flowing granular material can arrest abruptly when subjected to a sub-critical shear stress. Furthermore, the flow-arrest transition is highly stochastic in nature, with important implications in industrial materials handling such as hopper flow, and geophysical phenomenon such as landslides. Ref: [Srivastava et al., *Phys. Rev. Lett.*, 122 (2019)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.122.048003).

<div class="row">
    <div class="col- mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Fig1.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Left: Flow-arrest bifurcation. Right: Diverging arrest times as a function of applied shear for different inter-particle friction (increasing L-R).
</div>

We developed a contact mechanics model for non-spherical faceted particle interactions. Using this model we studied the phenomenon of jamming of frictionless platonic solids under external hydrostatic stress. Furthermore, we also highlighted the local micromechanics during slow creep deformation of such jammed solids. Refs: [Srivastava et al., *Soft Matter*, 13 (2017)](https://doi.org/10.1039/C7SM00237H) and [Smith, Srivastava et al., *Phys. Rev. E*, 89 (2014)](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.89.042203).

<div class="row">
    <div class="col- mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Fig2.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    (L-R): Local strain distribution in packings of tetrahedra with the progression of creep under constant external uniaxial stress.
</div>

<div class="row">
    <div class="col- mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Fig3.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Jamming volume fraction for different particle shapes.
</div>

Other publications:

[Srivastava et al., *Granular Matter*, 22, 41 (2020)](https://link.springer.com/article/10.1007/s10035-020-1003-6)

[Srivastava et al., *arXiv:1912.04491*](https://arxiv.org/abs/1912.04491)

## mesostructural analysis of lithium-ion battery electrodes

Lithium-ion battery cathodes typically contain four phases: (1) micron-sized active material particles (such as nickel-manganese-cobalt oxides); (2) electron-conducting carbon nanoparticles; (3) polymeric binders; and (4) ion-conducting electrolytes. Identifying the toplogical arrangements of these phases in real electrodes is experimentally challenging, but is crucial for battery performance. Using large-scale (~10 million particles) coarse-grained colloidal and granular numerical methods, we simulate the mesostructural evolution of electrodes during manufacturing, and correlate with their electrochemical performance. We highlight the complex transport within these highly heterogeneous electrode mesostructures, and provide predictions for improving electrode performance through the optimization of material properties. Ref: [Srivastava et al., *ACS Appl. Mater. Interfaces*, (2020)](https://pubs.acs.org/doi/10.1021/acsami.0c08251). 

<div class="row">
    <div class="col- mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Fig4.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Cohesion between active material particles and carbon-binder domain significantly impacts mesostrucutre of Li-ion battery electrodes.
</div>

Other Publications:

[Srivastava et al., *J. Heat Transfer*, 135 (2013)](https://asmedigitalcollection.asme.org/heattransfer/article-abstract/135/6/061603/367161)

## mechanics of nanoparticle superlattices

Polymer-grafted metallic nanoparticles readily self-assemble into three-dimensional superlattices with long-ranged order. These materials have important applications in photonics, plasmonics and catalysis. Furthermore, it was recently shown that such three-dimensional superlattices can be readily transformed into low-dimensional ordered nanostructures (such as nanowires and nanosheets) by applying large stresses, thus providing a well-controlled nanostructure fabrication method. The mechanics of such transformations, however, is not entirely understood. Using large-scale atomic simulations, we predict the mechanics of alkanethiol-grafted gold nanoparticle superlattices under high external pressure up to 15GPa. Unexpected phenomena such as void collapse and nanoparticle sintering were observed that challenge current theoretical models. Future work includes understanding the role of temperature, nanoparticle size and solvent properties on these phenomena. Ref: [Srivastava et al., *J. Phys. Chem. C*, 123 (2019)](https://pubs.acs.org/doi/abs/10.1021/acs.jpcc.9b02438)

<div class="row">
    <div class="col- mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Fig5.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    An FCC nanoparticle superlattice unit cell under external hydrostatic stress.
</div>

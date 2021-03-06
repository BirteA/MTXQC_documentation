---
always_allow_html: yes
---

# Appendix - Protocols{#protocols}

## Materials{#materials}




## Solutions{#solutions}
### Label buffer{#washingbuffer}

Materials:

* ddH2O (500 ml)
* 140 mM NaCl (4.1 g)
* 5 mM Hepes (0.569 g)
* pH calibration 7.4

Procedure:

* Weigh the correct amounts of Hepes and NaCl
* Resolve in a glas bottle with 450 ml of water
* Stir carefully
* Check and adjust pH
* Adjust volumes to 500 ml

### MCW{#mcw}

Materials:

* Methanol
* Chloroform
* ddH2O
* Cinnamic acid stock in MeOH (2 mg/ml): final conc. 2 ug/ml

Procedure:

* Mix the solvents in the ratio of volumes - Methanol:Chlorofom:Water -- 5:2:1
* Supplement cinnamic acid stock 1:1000
* Store at -25&deg;C

### Alkane-Mix{#alkanemix}

Materials:

* Hexane
* Alkanes: c10, c12, c15, c17, c19, c22, c28, c32, c36
* Thermo mixer
* Glass vials and caps

Procedure:

* Prepare stock solutions in hexane:
  + c10 - c17 (liquid): 25 ul/ml
  + c19 - c32: 20 mg/ml
  + c36: two-times 15 mg/1.5 ml
* Warm up alkane stocks in thermo mixer 40&deg;C
* Prepare a text mixture in equal amounts, e.g., 50 ul each, but use twice the volume of c36
* Mix test mixture with MSTFA: 10 ul / 1 ml MSTFA
* Check alkane profile by GC-MS
* If required: adjust volumes and re-test or create larger volume of zour mixture for aliquots
* Store aiquots in glass vials, close well and store at 4&deg;C
* For usage: gently warm up glass vials at 30 C on thermo mixer for 10 min and vortex before adding it to the MSTFA

Adjust the volumes of the alkane stocks in order to create a curve shaped distribution of all alkanes in the chromatogram: lower intensities for c10 and c32-36, slowly increasing intensities for the alkanes in between.

## Idents \& Quant-Standards{#standards}

has to be written


## Sample Extraction{#SampleExtraction}
### Cell extracts

Materials:

- cell culture dishes (10 cm), max. confluency 75\%
- washing buffer (Hepes, NaCl, ph 7.4)
- 50\% MeOH, ice-cold
- 2 mg/ml cinnamic acid
- chloroform
- 15 ml falcon tubes
- cell lifter

Procedure:

- prepare cell culture dishes accordingly to your experimental conditions
- discard cell culture media
- add quickly 5 ml of washing buffer, discard it
- add very immediately 5 ml ice-cold 50\% MeOH suppl. 2 ug/ul cinnamic acid
- detach cells using cell lifter
- collect and transfer cell extract into 15 ml falcon
- store falcons until further processing on ice
- add 1 ml chloroform
- incube for 60 min at cold temperatures (4 C) on rotary or thermo shaker
- centrifuge at max speed for 10 min, cold temperatures
- collect polar and lipid phases into fresh falcons / tubes
- dry under vacuum

In order to generate technical backups:

- resuspend dried extracts in 600 ul 20\% MeOH
- shake at cold temperature on thermo shaker for 30 min
- split volumes into equal parts in fresh eppendorf tubes
- dry under vacuum

Suggested cell density: $2-3e+6$ cells / extract.

### Tissue samples

Materials:

- Methanol:Chloroform:Water (MCW) in ratio 5:2:1
- 2 mg/mg cinnamic acid in MeOH
- ddH20
- eppendorf tubes
- tissue lyzer / pulverizer

Procedure:

- snap-freeze tissue samples
- pulverize samples
- aliquote 50 mg of tissue powder
- add 1.5 ml of MCW (suppl. with cinnamic acid final conc. 2 ug/ul)
- shake for 60 min on rotary shaker at cold temperature (4 C)
- add 0.5 ml ddH20 for phase separation
- centrifuge maximum speed, 10 min, cold temperatures
- collect polar and lipid phases in fresh vessels
- dry under vacuum


### Blood samples

Material:

- Methanol:Chloroform:Water (MCW) in ratio 5:2:1
- 2 mg/mg cinnamic acid in MeOH
- ddH20
- eppendorf tubes 

Procedure:

-	give 20 ul blood / sera directly into 1 ml MCW to avoid lumps
- in case of lumps sonicate samples
- shake samples at 4 C for 800 rpm for 60 min
- add 500 ul ddH20 and vortex shortly
- spin down at 4 C at max speed for 10 min
- aliquote polar phase into 2-3 times 500 ul in 1.5 ml tubes
- aliquote lipid phase 2 times in 100 ul lower in 1.5 ml eppi
- dry in SpeedVac (35 C)

## Derivatisation for GC-MS{#Deriv}

Materials:

- Methoxamine (MeOx)
- Pyridine (open under the hood only!)
- MSTFA
- Alkane mix (c10-c36) in Hexane
- chromacol vials and caps (big, small)
- samples: extracted and speed-vac dry for min 30 min prior procedure
- quant-standards: extracted and speed-vac dry
- ident-standards: extraction not required, speed-vac dry

Mixtures:

- Solvent 1: 40 mg MeOx in 1 ml Pyridine
- Solvent 2: 10 ul Alkane mix in 1 ml MSTFA

Volumens of both solvents are shown for standard (small vol.) procedures.

Procedure:

- make sure samples are completly dry (1 h speed vac)
- add 20 ul (10 ul) of solvent 1 / sample
- incubate on rotary shaker, 30 C, for 60 min
- add 80 ul (25 ul) of solvent 2 / sample
- incubaate on rotary shaker, 37 C, for 90 min
- centrifuge to spin down insoluble materials
- prepare aliquotes three times 28 ul or two times 15 ul (small glass vials)
- keep on room temperature until measurement (max. 10 days)




## GC-MS settings{#gcms}

In the following paragraphs details of GC-MS settings are described in detail. The herein described settings have been optimized for cell extracts measured in split-mode 1:5 on the instrument Pegasus 4D-C GC-ToF-MS in 1D mode equiped with an autosampler Gerstel MPS.

<!-- ### Autosampler settings -->

<!-- The table \@ref(tab:gerstel) summarises the defined parameter for method settings of the Gerstel MPS. -->

<!-- ```{r gerstel, echo=FALSE} -->
<!-- library(magrittr) -->
<!-- library(kableExtra) -->

<!-- mps = read.csv("example/tables/mps_settings.csv", TRUE) -->

<!-- #knitr::kable(mps, booktabs = TRUE, caption = "Parameter of Gerstel MPS settings") -->
<!-- #  -->
<!-- # knitr::kable(mps, booktabs = TRUE, caption = "Parameter of Gerstel MPS settings") %>% -->
<!-- #    kable_styling() %>% -->
<!-- #    group_rows(index = c("System" = 3,  -->
<!-- #                        "MPS Liq. Inj." = 15, -->
<!-- #                         "MPS Rinse" = 8)) -->


<!-- ``` -->

<!-- The injector itself is a temperature-regulated system providing the advantage of a focused injection of the sample. Gradient  -->

<!-- ```{r cis, fig.cap="Settings temperature-regulated injection for Gerstel MPS", echo=FALSE, fig.width=6} -->

<!-- knitr::include_graphics("images/cis.PNG") -->

<!-- ``` -->


<!-- ### Gas chromatography -->

<!-- The most important settings of the GC method are listed below. A graphical representation of the gradient in the oven is shown in figure \@ref(fig:gradient) and corresponding values in table \@ref(tab:gradient2). -->

<!-- Flow path: -->

<!-- 1. Inlet: Front -->
<!-- 2. Capillary: GC Oven 50 m, 250 u int. diameter, 0.25 u film thickness, RTX-5 phase -->
<!-- 3. Capillarty: Detector 0.21 m, 250 u int. diameter, 0.25 u film thickness, RTX-5 phase -->
<!-- 4. Detector: TOF -->


<!-- ```{r gc, echo=FALSE} -->

<!-- mps = read.csv("example/tables/gc_settings.csv", TRUE) -->

<!-- #knitr::kable(mps, booktabs = TRUE, caption = "Parameter of Gerstel MPS settings") -->
<!-- #  -->
<!-- # knitr::kable(mps, booktabs = TRUE, caption = "Parameter of Gerstel MPS settings") %>% -->
<!-- #    kable_styling() %>% -->
<!-- #    group_rows(index = c("System" = 2,  -->
<!-- #                        "Front Inlet" = 5, -->
<!-- #                         "Oven" = 3)) -->


<!-- ``` -->


<!-- ```{r gradient, echo=FALSE, fig.cap="GC gradient - graphical representation. Rate in (&deg;C/min), Target temperature in (&deg;C), Duratin in (min)."} -->
<!-- knitr::include_graphics("images/gradient.PNG") -->

<!-- ``` -->

<!-- ```{r gradient2, echo=FALSE} -->

<!-- grad = data.frame(Rate = c("Initial", 5, 7, 12), -->
<!--                   Target_Temp = c(68, 120, 200, 320), -->
<!--                   Duration = c( 2, 0, 0, 6)) -->

<!-- kable(grad, booktabs = TRUE, caption = "GC gradient profile - Rate shown in (K/min), Target Temp in (C), Duration in (min)") -->

<!-- ``` -->

<!-- ### Mass spectrometer settings -->

<!-- ```{r ms, echo=FALSE} -->

<!-- mps = read.csv("example/tables/ms_setting.csv", TRUE) -->

<!-- #knitr::kable(mps, booktabs = TRUE, caption = "Parameter of Gerstel MPS settings") -->
<!-- # #  -->
<!-- # knitr::kable(mps, booktabs = TRUE, caption = "Parameter of Gerstel MPS settings") %>% -->
<!-- #    kable_styling() %>% -->
<!-- #    group_rows(index = c("Filament" = 4,  -->
<!-- #                        "Mass detection" = 7, -->
<!-- #                         "Ion source" = 3)) -->


<!-- ``` -->




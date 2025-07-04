<!-- PageHeader="Fusion Engineering and Design 146 (2019) 2323-2327" -->


<figure>

ELSEVIER

</figure>


<!-- PageHeader="Contents lists available at ScienceDirect" -->

Fusion Engineering and Design
journal homepage: www.elsevier.com/locate/fusengdes

2
Fusion Engineering
and Design


# Assessment of the activation induced by neutron irradiation in K-DEMO and thermal response under the decay heat


<figure>

Check for
updates

</figure>


Beom Seok Kim*, Byung Chul Kim, Kihak Im, Hong-Tack Kim, Sungjin Kwon, Jongsung Park
National Fusion Research Institute, DEMO Technology Division, 169-148 Gwahak-ro, Yuseong-gu, 34133, South Korea


## ARTICLE INFO

Keywords:
K-DEMO
Breeding blanket
Divertor
Radioactivity
Decay heat
Thermal analysis
Heat transfer
Cooling


## ABSTRACT

The radioactivation of in-vessel components due to the fusion neutrons is an unavoidable trade-off in a tokamak
reactor. We investigate the radioactivity level of nuclides and decay heat of conceptual water-cooled ceramic
breeder blanket and divertor modules in K-DEMO, and demonstrate that a cooling scheme related to the decay
time is important to prevent thermal failure of those components due to decay heat during their maintenance.
For K-DEMO with a fusion power of 2.2 GW, the activation levels of blankets and divertors are evaluated
regarding a regulatory low level limit in Korea. Total decay heat from radioactivated blankets and divertors
reaches 63.4 MW after the full power operation of two years. In an outboard module, immediately after the
plasma shutdown, local maximum temperature reaches 1300℃ with the temperature difference up to 840 ℃
inside the module. Conservative natural convection was assumed to validate its integrity to remain within the
allowable temperature range of the materials used, when provided that the cool-down time is secured at least a
couple of days, the overall temperature of the module is reduced to about 200℃ in 10 days. It is worth con-
sideration that a forced convective scheme such an internal passage cooling can be tailored until a critical time
corresponding to configurations of each module.


## 1. Introduction

It is necessary to manage the radioactivity of in-vessel components
at a low level and resulting decay heat against their radioactivation due
to fusion neutrons although absence of high-level radioactive waste is a
great advantage of nuclear fusion power [1-4]. It is foreseen that
subsequent decay heat generation from used in-vessel components,
such as blankets and divertors, reaches up to tens of megawatt after the
plasma shutdown [2,3,5,6]. During the maintenance involving the re-
placement of in-vessel components, the induced radionuclides, their
concentration and decay heat restrict application conditions of remote
handling technology. Moreover the induced radioactivation character-
istics are critical determinants of disposal methods of the radio-acti-
vated components as radiowaste to be [7].

The issue in radioactivation is very important for the design of K-
DEMO, particularly for the safety of the reactor [8,9]. A preliminary
assessment has to be done to verify whether it can be handled within
the scope of intermediate level radioactive waste in accordance with
related regulations. The compliance with the regulatory procedures will
lead to the optimization of maintenance technologies (i.e., remote
handling) [10-12] not only to minimize the amount of radioactive
waste but also to maximize the availability of a fusion plant [3,13].

In this study we aim to investigate the radioactive characteristics of
a conceptual water-cooled ceramic breeder blanket and a divertor
module in K-DEMO. The concentrations of activated nuclides from
blankets and divertors are evaluated, and subsequent decay heat is
estimated. Accounting for the decay heat analysis, we estimate their
thermal response of temperature distributions by 3-D heat transfer
analyses using ANSYS Fluent. We demonstrate that cool-down time of
components is a key factor in designing a cooling scheme. It is worth
consideration that an active cooling, which dissipates heat by a primary
heat transfer system passing through the in-vessel components, can be
tailored to ensure soundness of the components and optimize a main-
tenance scenario without their failure.


## 2. Specification of K-DEMO for the assessment of rad-waste

Fig. 1 shows the schematic of the conceptual K-DEMO tokamak
reactor equipped with water-cooled ceramic breeder blankets and di-
vertor modules [14-17]. The tokamak with a fusion power of 2.2 GW is
a double null with vertically symmetrical divertors, and has a major
radius (R) of 6.8 m and minor radius (a) of 4.2 m [18,19]. A breeding
blanket induces sustainable tritium breeding and neutron multi-
plication through a reaction between neutrons emitted from fusion

\* Corrsponding author.

E-mail address: kimmbs@nfri.re.kr (B.S. Kim).

<!-- PageFooter="https://doi.org/10.1016/j.fusengdes.2019.03.181" -->
<!-- PageFooter="Received 27 September 2018; Received in revised form 26 March 2019; Accepted 27 March 2019 Available online 16 April 2019" -->
<!-- PageFooter="0920-3796/ @ 2019 Elsevier B.V. All rights reserved." -->
<!-- PageBreak -->

<!-- PageHeader="B.S. Kim, et al." -->
<!-- PageHeader="Fusion Engineering and Design 146 (2019) 2323-2327" -->


<figure>
<figcaption>Fig. 1. Schematic of K-DEMO tokamak design [15,18,19].</figcaption>

R

In-/outboard

blanket

Divertor

2ª

</figure>


plasma and materials of breeder and multiplier, respectively. The
water-cooled ceramic breeder blanket consists of a plasma facing layer
of tungsten, a structural material of reduced activation ferritic mar-
tensitic (RAFM) steel and pebble bed layers of Li4SiO4 and Be12Ti
contained in RAFM steel structures for the respective tritium breeding
and neutron multiplication [15,20]. It is a modular component and
hundreds of the modules constitute tokamak inner wall [15]. A divertor
consists of tungsten mono-blocks, to ensure mechanical robustness
against high heat flux, RAFM steel heat sinks and a cassette body with
internal

cooling passages [20-22]. In both models, internal cooling passages
are shaped for a pressurized water coolant [15,17,21,23]. Table 1
presents the weight of conceptual modules of K-DEMO blanket and
divertor components discharged at every replacements.


## 3. Assessment of radioactivation of in-vessel components

The neutron wall load (NWL) applied to plasma facing surfaces is
calculated for the fusion power of 2.2 GW. Local NWL on the first wall
(FW) is estimated using a developed in-house code [24]. When the
geometric information is set first, the plasma region, where is for the
plasma core and the scrape-off layer (SOL), and the FW are to be seg-
mented. Then it calculates the quantity of the neutron load distribution
from each source (i.e., plasma radiation and neutron) point to each
target segment on FW considering the solid angles. Fig. 2 shows NWL
applied to the in-vessel components in the poloidal direction. An
average NWL applied to the FW of the in-vessel components exceeds
1 MW/m2, and FW of an equatorial outboard blanket is exposed to
2.83 MW/m2. Accounting for this profile, we analyze the radio-
activation level and decay heat generation of the water-cooled ceramic
breeder blanket and divertor by an in-house code utilizing a nuclide
emission data library [25,26]. In the calculation process using this code,
it is assumed that the in-vessel components are exposed to the fusion
neutrons irradiated from the reactor for 2 years. In addition the blanket
and the divertor components are handled as 1-D layered models as


<table>
<caption>Table 1 Weight of in-vessel components.</caption>
<tr>
<th>Components</th>
<th>Layer</th>
<th>Weight [ton]</th>
</tr>
<tr>
<td rowspan="3">Blanket</td>
<td>W</td>
<td>49.42</td>
</tr>
<tr>
<td>RAFM</td>
<td>526.7</td>
</tr>
<tr>
<td>Pebbles</td>
<td>335.4</td>
</tr>
<tr>
<td rowspan="2">Divertor</td>
<td>W</td>
<td>120.0</td>
</tr>
<tr>
<td>RAFM</td>
<td>1211</td>
</tr>
</table>


<figure>
<figcaption>Fig. 2. Neutron wall loading profile on the in- and outboard blanket (I-BB and O-BB) and divertor (DV).</figcaption>

3.5

Neutron wall load [MW/m2]

I-BB

DV

3.0

O-BB

in-

central

out-

2.83

2.5

2.20

2.0

1.5

1.0

0.5

0.0

0

10

20

30

40

50

60

Segment No. in poloidal direction

</figure>


<figure>
<figcaption>Fig. 3. Schematic of in-vessel components of breeding blanket and divertor module. 1-dimensional structure of (a) the water-cooled ceramic breeder blanket and (b) divertor module for radioactive characteristics analysis [5,6].</figcaption>

(a)

W RAFM

Cooling tube (RAFM + H2O)

Pebble bed (Li SiO4 + Be12 Ti)

V

...

...

neutrons

\-

\-

\-

\-

y

Z

(b)

W monoblock
Support (RAFM)

RAFM

Cooling tube (RAFM + H2O)

neutrons

\-

\-

\-

\+

\+

\+

\+

\-

y

Z

</figure>


schematically presented in Fig. 3. In a blanket model a plasma facing W
layer, an adhesion layer of vanadium, RAFM steel structures and the
pebble beds are represented by a series of layer structures. The 1-D
divertor model describes tungsten mono-blocks, heat sinks made of
RAFM steel and a cassette body. Through

the neutron transport analysis using a Monte Carlo neutron particle
transport code (MCNP), the neutron flux is derived to each layer in the
1-D model according to refined energy levels from 10-10 to 14.1 MeV
[20]. Then the degree of neutron flux attenuation along the depth of the
modules is correlated as a function of position, and extrapolated on
every surfaces and cells constituting the model in terms of configura-
tions (i.e., shapes and materials) of each blanket and divertor. The
radioactivity and consequent decay heat characteristics are then
quantitatively derived as a function of time and position of each con-
stituent element of the structure [20]. Accounting for the decay heat
after plasma shutdown, the consequent thermal behaviors of the com-
ponents are characterized by 3-D heat transfer analyses using an ANSYS
Fluent (v18.0) software under quasi-steady state conditions according
to the time increase.


## 4. Radioactivity and classification of the waste

Fig. 4 shows the time-dependent radioactivity originated from the
blanket and divertor mounted in the tokamak. The plasma facing
tungsten layer shows a high activation in both blanket and divertor. It

<!-- PageNumber="2324" -->
<!-- PageBreak -->

<!-- PageHeader="B.S. Kim, et al." -->
<!-- PageHeader="Fusion Engineering and Design 146 (2019) 2323-2327" -->


<figure>
<figcaption>Fig. 4. Radioactivity concentrations on the breeding blanket and the divertor under 2.2 GW fusion power of K-DEMO. A dotted blank line indicates the comparison result on a tungsten coating layer of a breeding blanket in a re- ference of Japanese DEMO study [13].</figcaption>

Time, t [d]

R-activity concentration [Bq/kg]

10º

101

103

1016

10-2

10-1

102

104

105

1015

Blanket W coating (J-DEMO) [13]

1014

1013

1012

1011

1010

Breeding blanket

Divertor

109

W

--- W

108

RAFM

structure

\- RAFM

support

pebbles

RAFM

cassette

10

106

10 10-4 10-3 10-2 101 100 101 102 103

Time, t [y]

</figure>


<figure>
<figcaption>Fig. 5. (a) Radioactivity and low level boundaries of nuclides from the tungsten first wall in outboard breeding blanket. (b) Classification of radioactive waste and resultant disposal methods based on a Korean regulation [27-29].</figcaption>

(a) 1011

°Co(3.70E10)

1011

60Co

Specific activity [Bq/kg]

1010

3Ni(1.11E10)

1010

Low level limit [Bq/kg]

109

3H

3H,137Cs(1.11E9)

14C(2.22E8)

109

108

108

63 Ni

59Ni & 90Sr

(7.40E7)

10

14C

107

106

137

Cs

99Tc (1.11E6) +

106

105

99TC

90gr

105

104

59 Ni

104

103

10-3

10-2

10-1

10º

101

102

103

10

103

Time, t [y]

</figure>


(b)

High Level Waste (HLW)

Deep geological disposal

Intermediate Level Waste (ILW)

Underground carven

Low Level Waste (LLW)

Engineered

Shallow land

Near field disposal

Very Low Level Waste (VLLW)

Landfill disposal

can be stated the cooling time after plasma shutdown is a deterministic
factor of their radioactivity and a design parameter of maintenance
[13]. The activation levels of W in the blanket and divertor decrease in
time and become 3.16% and 3.50% in a year compared to their initial
values, respectively. Fig. 5a shows activated nuclides from the tungsten
FW located in an equatorial outboard blanket where the highest

radioactivation is predicted with NWL of 2.83 MW/m2. In the graph,
baselines which specifies low level limit of rad-wastes in Korea are also
indicated [27]. Fig. 5(b) explains the classification of rad-waste and
corresponding disposal methods in Korea [13,27-29]. The rad-waste
should be handled in accordance with the regulation and be indicated
into the low level waste, which can be disposed of in shallow land
burial in the light of social and economic susceptibility of a fusion plant.
Considering the baselines, we confirm that long-half-life radionuclides
such as 14℃ (t1/2 = 5700 y), 60Co (t1/2 = 5.27 y) and 99Tc (t1/
2 = 2.1 x 105 y) can be kept below their specific baseline activity of
3.74 x 106, 3.02 × 1010 and 1.41 x 105 Bq/kg, respectively. The re-
sults demonstrate those noxious nuclides remains below the low level
limit. The replacement of the components and disposal must be per-
formed depending on the level of activity concentrations [26]. In other
words, the legitimate classification as shown in Fig. 5b will be a
guideline for designing a maintenance period and a consequential dis-
posal method regarding the activation.


## 5. Assessment of decay heat for cooling design

For thermal analyses, a commercial computational fluid dynamic
code of ANSYS Fluent (v18.0) was used as a solver. For the blanket and
divertor modules, 3-dimensional temperature on both blanket and di-
vertor modules was evaluated under a quasi-steady state condition.
Particularly on blanket models, preliminary mesh dependence were
checked, and structured meshes more than 1.9 million were used with
at least 7 layers in the thinnest structure. Natural convection excluding
other cooling schemes is assumed on the outmost surface of a target
module with heat transfer coefficient of 10 W/m2K for conservative
assessment of thermal reliability.

Fig. 6 shows the variation of decay heat from the in-vessel compo-
nents. Immediately after the plasma shutdown, the in- and outboard
blanket and the divertor generate decay heat by 13.0, 42.1 and
8.34 MW, respectively. Total decay heat drastically decreases from 63.4
(at t = 0 s) to 7.44 (11.0%), 3.16 (4.97%), 2.82 (4.44%) and 2.55 MW
(4.02%) as t increases to 1, 7, 15 and 30 days, respectively. Consequent
local temperature is also evaluated to validate whether it would be
secured below their melting points. In case of a divertor (Fig. 7(a)), the
maximum temperature of a divertor readily decreases with time; a se-
parate divertor shows the highest temperature of 418.3, 336.6 and


<figure>
<figcaption>Fig. 6. Decay heat of the components after the plasma shutdown. O-BB, I-BB and DV indicate the outboard breeding blanket, the inboard breeding blanket and the divertor, respectively.</figcaption>

Time, t [d]

10-2

10-1

10º

101

102

103

104

105

102

101

BB + DV

O-BB

Decay heat, Q [MW]

10º

I-BB

DV

10-1

100

[MW]

t=0 s

4 d

O-BB

42.1

2.22

10-2

10

1 -BB

13.0

0.685

Q [MW]

DV

8.34

0.857

10-3

1

10-

10-5

0.1

0

1

2

3

4

t [d]

10-6

10-

10-4

10-3

10-2

10-1

10º

101

102

103

Time, t [y]

</figure>


<!-- PageNumber="2325" -->
<!-- PageBreak -->

<!-- PageHeader="B.S. Kim, et al." -->
<!-- PageHeader="Fusion Engineering and Design 146 (2019) 2323-2327" -->


<figure>
<figcaption>Fig. 7. (a) Local maximum temperature of a divertor module. (b) Local tem- perature of an outboard blanket located at equatorial port. The red-colored lines with solid and blank circles are the local maximum and the minimum temperature in the blanket, respectively. The black-colored bar graphs is the temperature difference in the blanket. Inset shows temperature contours in the blanket module just after the plasma shutdown (For interpretation of the re- ferences to colour in this figure legend, the reader is referred to the web version of this article).</figcaption>

Max. temperature, Tmax [°℃]

440

440

400

360

360

[ºC]

280

320

max

200

A

280

120

240

40

0.00

0.25

0.50

0.75

1.00

200

t [d]

160

Central part

120

Outboard target

80

Inboard target

40

0

0

4

8

12

16

20

24

28

32

(b)

Time, t [d]

1000

Temperature, T [C]

1400

T

1375

1200

max

T

800

AT (Tmax - Tmin) [°C]

1000

min

T (℃)

AT

x

Z

600

800

0

y

x

600

0

2

400

487.4

400

200

200

0

0

0

2

4

6

8

10

12

14

16

Time, t [d]

</figure>


216.3 °℃ in central-,

outboard- and inboard target, respectively. For the central part it
takes at least 3 days while overall temperature falls below 100 ℃. In an
outboard blanket module (Fig. 7(b)), decay heat leads to local tem-
perature increase over 1300 ℃ and spatial temperature difference of
840 ℃ within a module. Otherwise, the natural convection without any
forced convective cooling can be valid only after the specific cool-down
period of at least a couple of days; local maximum temperature in the
blanket decreases to 220 ℃ and 180 ℃ with the time of 4 and 10 days,
respectively. These results demonstrate the cool-down time is important
in designing a maintenance scheme. Particularly in the specific period
with high decay heat, the significant temperature difference might lead
to unexpected failure due to consequent thermal stresses. In this regard,
an appropriate cooling scheme involving an active cooling through
internal passages of in-vessel components should be employed con-
sidering the transient thermal behaviors, which depend on configura-
tions of each component.

It is important that each component should be as intact as possible,
and related facilities be prevented from being damaged due to thermal
failure induced by decay heat. In order to minimize the volume of
radioactive waste, an optimal maintenance scheme should be devised
through the reuse or recycling of materials used for the in-vessel
components. Furthermore, the decay heat should be regarded as a
primary source term deteriorating the safety of a DEMO system

[8,30,31]. The conservative assessment on safety issues, assuming the
worst accidents, and sequential feedback on design will be the basis of
our future studies for the design of a reliable fusion plant.


## 6. Conclusion

The radioactivation of in-vessel components is inevitable in a fusion
tokamak reactor. In a design phase of a DEMO, the concentration of
radioactive nuclides and decay heat should be treated as factors de-
termining a replacement and subsequent disposal strategy of in-vessel
components. In this study we investigated the activation levels of water-
cooled ceramic breeder blankets and divertors in K-DEMO in respect to
a regulatory low level limit in Korea. We assessed decay heat genera-
tion; total decay heat from the in-vessel components reaches up to
63.4 MW after two years of the full power operation of a conceptual K-
DEMO with the target fusion power of 2.2 GW. It is worth consideration
that alternative cooling schemes involving an active cooling can be
tailored at the time when excessive decay heat occurs. The activation
characteristics will be further assessed for the global K-DEMO model,
and will be discussed to clarify design parameters of hot cell and related
maintenance scenarios [12]. The integrated decay heat results will also
be employed as prerequisites of a transient thermo-hydraulic analysis
for safety assessment of K-DEMO.


## Acknowledgements

This research was supported by R&D Program of "Study of
Demonstration Plant Design Concept and Base Technology (CN1801)"
through the National Fusion Research Institute of Korea (NFRI) funded
by the Government funds.

References

[1] T. Eade, et al., Activation and decay heat analysis of the European DEMO blanket
concepts, Fusion Eng. Des 124 (2017) 1241.

[2] Y. Someya, et al., Management strategy for radioactive waste in the fusion DEMO
reactor, Fusion Sci. Technol. 68 (2015) 423.

[3] Y. Someya, et al., Waste management scenario in the hot cell and waste storage for
DEMO, Fusion Eng. Des. 89 (2014) 2033.

[4] P. Pereslavtsev, L. Lu, U. Fischer, O. Bitz, Neutronic analyses of the HCPB DEMO
reactor using a consistent integral approach, Fusion Eng. Des. 89 (2014) 1979.

[5] B. S. Kim et al. Analysis on the radio-activation and decay heat induced by fusion
neutrons in K-DEMO breeding blanket, J. Korean Soc. Mech. Eng., In press.

[6] Y. Someya, K. Tobita, Estimation of decay heat in fusion DEMO reactor, Plasma
Fusion Res. 7 (2012) 2405066.

[7] F. Cismondi, et al., Progress in EU-DEMO in-vessel components integration, Fusion
Eng. Des. 124 (2017) 562.

[8] N. Taylor, et al., Preliminary safety analysis of ITER, Fusion Sci. Technol. 56 (2009)
573.

[9] J.S. Park, K. Im, B.C. Kim, S. Hong, Shutdown dose rate calculation for the pre-
liminary concept of K-DEMO equatorial port area, IEEE Trans. Plasma Sci. 46
(2018) 1713.

[10] C. Bachmann, et al., Overview over DEMO design integration challenges and their
impact on component design concepts, Fusion Eng. Des. 136 (2018) 87.

[11] R. Buckingham, A. Loving, Remote-handling challenges in fusion research and be-
yond, Nat. Phys. 12 (2016) 391.

[12] J. Thomas, A. Loving, C. Bachmann, J. Harman, DEMO hot cell and ex-vessel re-
mote handling, Fusion Eng. Des. 88 (2013) 2123.

[13] Y. Someya et al., Safety and waste management studies as design feedback for a
fusion DEMO reactor in Japan, 26th IAEA Fusion Energy Conference (2016) SEE/
P7-5.

[14] Y. Kawamura, et al., Status of water cooled ceramic breeder blanket development,
Fusion Eng. Des. 136 (2018) 1550.

[15] J.S. Park, et al., Pre-conceptual design study on K-DEMO ceramic breeder blanket,
Fusion Eng. Des. 100 (2015) 159.

[16] H. Lee, et al., Thermal-hydraulic analysis of water cooled breeding blanket of K-
DEMO using MARS-KS code, Fusion Eng. Des. 98 (2015) 1741.

[17] L. Barucca, et al., Status of EU DEMO heat transport and power conversion systems,
Fusion Eng. Des. 136 (2018) 1557.

[18] K. Kim, et al., Design concept of K-DEMO for near-term implementation, Nucl.
Fusion 55 (2015) 053027.

[19] T. Brown, et al., Progress in developing the K-DEMO device configuration, IEEE
25th Symposium on Fusion Engineering (SOFE), (2013).

[20] J.S. Park, K. Im, S. Kwon, Development of neutronics model for the K-DEMO water
cooled ceramic breeder blanket with MCNP code, IEEE 26th Symposium on Fusion

<!-- PageNumber="2326" -->
<!-- PageBreak -->

<!-- PageHeader="B.S. Kim, et al." -->
<!-- PageHeader="Fusion Engineering and Design 146 (2019) 2323-2327" -->

Engineering (SOFE), (2015).

[21] Y. Huang, et al., Thermo-structural design of the European DEMO water-cooled
blanket with a multiscale-multi physics framework, Fusion Eng. Des. 135 (2018) 31.

[22] S. Kwon, J.S. Park, K. Im, Thermo-mechanical evaluation of a water cooled high
heat flux unit for the K-DEMO divertor, IEEE 26th Symposium on Fusion
Engineering (SOFE), (2015).

[23] K. Im, S. Kwon, J.S. Park, A preliminary development of the K-DEMO divertor
concept, IEEE Trans. Plasma Sci. IEEE Nucl. Plasma Sci. Soc. 44 (2016) 2493.

[24] K. Im, Evaluation of Plasma Radiation Heat Load and Neutron Wall Loading, K-
DEMO Report TN035-2017-In-vessel-004, NFRI, 2017.

[25] M.R. Gilbert, J. Sublet, R.A. Forrest, Handbook of activation, transmutation, and
radiation damage properties of the elements simulated using FISPACT-II & TENDL-
2014; magnetic fusion plants, CCFE-R 26 (2015) 15.

[26] M.R. Gilbert, J. Sublet, A. Turner, Handbook of activation, transmutation, and

radiation damage properties of the elements simulated using FISPACT-II & TENDL-
2015; ITER FW Armour focus, CCFE-R 37 (2016) 16.

[27] Nuclear Safety and Security Commission, Regulations for Classification of
Radioactive Waste and Criteria on Clearance, Notice No. (2017), p. 65.

[28] J. Kim, et al., Characteristic analysis and optimum management plan of disused
sealed radioactive sources in Korea, Ann. Nucl. Energy 102 (2017) 268.

[29] J.S. Song, et al., A pre-study on the estimation of NPP decommissioning radioactive
waste and disposal coasts for applying new classification criteria, J. Nucl. Fuel Cycle
Waste Technol. 13 (2015) 45.

[30] M. Nakamura, et al., Study of safety features and accident scenarios in a fusion
DEMO reactor, Fusion Eng. Des. 89 (2014) 2028.

[31] M. Nakamura, et al., Key aspects of the safety study of a water-cooled fusion DEMO
reactor, Plasma Fusion Res. 9 (2014) 1405139.

<!-- PageNumber="2327" -->

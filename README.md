# FMC ADC 130M 16B 4CHA

## Project description

One of the most important goals in every light source is to achieve
orbit stability for the electron beam within the required specifications
for the stability of the photon beam in the experimental stations.
Several technical challenges make the task of achieving sub-micrometer
stability really demanding in terms of mechanical and electrical
engineering. Fast feedback systems are employed to dump orbit
distortions through accurate measurements of the beam positions, fast
computation of the corrections and actuation back to the beam through
fast power supplies and steering magnets. To realize this task in the
\*SIRIUS\*http://www.lnls.br, the new brazilian synchrotron light
source, a digital platform to measure the beam position is required.
Inside this plattaform a key part is the analog to digital conversion.
This text will describe the main specification for an FMC
Analog-to-digital conversion board.

There are several commercial off-the-shelf digitizers covering a wide
range of speed, bandwidth and resolution, but there is no board that
cover all features required for the LNLS
design.

-----

![](https://ohwr.org/project/fmc-adc-130m-16b-4cha/uploads/6dc90056516f03b08405e7f8b6f7ae54/fmc_top.jpg)

*FMC ADC 130M 16B 4CHA production board** - ([Top
view](https://www.ohwr.org/project/fmc-adc-130m-16b-4cha/uploads/23f18a16ba281e2f93acb31782c0db42/top_r.jpg), [Bottom
view](https://www.ohwr.org/project/fmc-adc-130m-16b-4cha/uploads/616fc42ba8aeb56efde3af8f24af65d3/bot_r.jpg), [Front
view](https://www.ohwr.org/project/fmc-adc-130m-16b-4cha/uploads/30c50ed58559d64d9c38bfc512450c89/fmc_bot.jpg) )

## Functional specifications

- VITA 57.1-2010 compliant
- Four Channel 16 bit 130 MSPS ADC. Required ADC: LTC2208IUP
- Internal ADC clock circuit: Phase locked to the external reference clock input with fine frequency tuning capability. See specific section. Hold mode in case of loss of external reference is a desirable feature.
- Internal high frequency PLL oscillator output with amplitude control and locked to external reference.
- External ADC clock input (50 MHz up to 130 MHz, 0 dBm typ.)
- External reference clock input: (0.5 MHz - 20 MHz digital signal, 0 dBm typ.)
- External digital Trigger input
- External digital Trigger output
-----
## Detailed project information
![Block		        diagram](https://www.ohwr.org/project/fmc-adc-130m-16b-4cha/uploads/7ebadad4b70fdcbb186367e2e662c0b1/diagramas_em_blocos_generico.jpg)

|Date|Activity|
|----|----|
|01/10/2011|First sudies about necessities|
|27/11/2011|FMC standard choosed|
|05/03/2012|Project started at OHWR|
|15/03/2012|ADC choosed|
|26/03/2012|power dissipation solutions studied|
|04/05/2012|Specification document V1.0 done|
|22/05/2012|Start of block diagram design: clock schemes, PS, input stage,FMC interface,etc|
|01/08/2012|Start collaboration with WUT/Creotech for boards design (130 and 250 MSPS versions)|
|22/10/2012|Start schematics and discussions with WUT/Creotech|
|03/12/2012|Decision of layout unification for reuse of heatsink in both boards|
|06/12/2012|Start of design modification, mechanical unification with FMC ADC 250M version|
|19/12/2012|Layout ready for review|
|21/12/2012|Fast review send from LNLS to WUT/Creotech|
|12/02/2013|Pre-assembled boards received by WUT/Creotech|
|14/02/2013|Start basic tests|
|26/04/2013|FMC ready, tested and assembled|
|30/09/2014|Available commercially|


													   													      
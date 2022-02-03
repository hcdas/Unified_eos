# Unified_eos
Unified equation of state (EOS) for neutron star

The core EOSs of the neutron star is calculated using relativistic mean-field model. 
For inner crust EOS is calculated using compressible liquid drop model (CLDM) model.
For outer crust EOS is calculated using availbale experimantal data such as FRDM 2012, AME 2020, 
and other therotical microscopic methods named as Hartree-Fock-Bogoliubov (HFB). 

This calculations use the Thomas Carreau code (https://github.com/thomascarreau/NSEoS)
This is the extentsion version for relativistic mean-field model.

Three unified EOSs are given named as eos_unified_FSUGarnet.dat, eos_unified_G3.dat and eos_unified_IOPB.dat.
First coulmn is baryon density (fm^-3), energy density (MeV/fm^3), pressure (MeV/fm^3)

If you are using these EOSs for your calculations, please cite the following article

Crustal properties of the neutron star within effective relativistic mean-field model
arXiv:2111.07278 (https://arxiv.org/abs/2111.07278)
PRD accepted

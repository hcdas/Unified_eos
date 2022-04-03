# Unified Equation of state (EOS)

The core EOSs of the neutron star is calculated using relativistic mean-field model. 
The inner crust EOS is calculated using compressible liquid drop model (CLDM) model.
The outer crust EOS is calculated using availbale experimantal data such as FRDM 2012, AME 2020, 
and other therotical microscopic methods named as Hartree-Fock-Bogoliubov (HFB). 

This calculations use the Thomas Carreau code (https://github.com/thomascarreau/NSEoS)
This is the extentsion version for relativistic mean-field model.

Three unified EOSs are given named as eos_unified_FSUGarnet.dat, eos_unified_G3.dat and eos_unified_IOPB.dat.
The coulmns are baryon density (fm^-3), energy density (MeV/fm^3), and pressure (MeV/fm^3)

If you are willing to use these EOSs for your calculations, please cite the following article

Crustal properties of the neutron star within an effective relativistic mean-field model
Phys. Rev. D 105, 043017 (2022), https://journals.aps.org/prd/abstract/10.1103/PhysRevD.105.043017 and 
arXiv:2111.07278 (https://arxiv.org/abs/2111.07278),

Unified EOSs with pasta inside the crust, please see https://github.com/hcdas/Unfied_pasta_eos

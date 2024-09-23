# RaEDM-Radiological-Hazard-Code

Python code for estimating the X-ray dose produced by the high voltage test
setup for the Radium EDM experiment. Includes an estimation of the X-ray power
spectrum which is used to estimate an absorbed dose. 

Copyright (C) 2024 Aiden Boyer

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>. 

Pyrex Attenuation Data:
col1: Energy [MeV]
col2: Mass attenuation with coherent scattering
col3: Mass attenuation without coherent scattering

linspace_points
This is generate data for 100 energy values (in MeV) that I plan to use for producing the attenuated X-ray data
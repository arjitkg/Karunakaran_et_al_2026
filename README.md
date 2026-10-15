{\rtf1\ansi\ansicpg1252\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww30040\viewh17640\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 \
_________________________________________________________________________________________________________________________________________________________________________\
\
Steps to successfully run the provided code and generate results and figures:\
\
1. Download motion-corrected calcium imaging imaging data here:\
\
2. Download this GitHub repository to your local machine and copy the downloaded data in step 1 inside this folder. Your folder structure should look like this:\
\
	Karunakaran_et_al_2026_manuscript\
		|_ csv_files\
		|_ data\
		|_ figures\
		|_ jupyter_notebooks\
		|_ metadata\
		|_ README.md\
		|_ LICENSE\
		|_ .gitignore\
\
3. Install these python libraries: tifffile, scipy, numpy, pandas, matplotlib, jupyterlab\
\
4. Open python terminal, navigate to the \'93Karunakaran_et_al_2026_manuscript\'94 directory and open jupyter lab.\
\
_________________________________________________________________________________________________________________________________________________________________________\
\
Data folder structure (representative):\
\
	AKG_B30\
		|_ csv_files - Contains raw fluorescence timeseries data for indicated recording and plane.\
			|_ R1_plane1_data.csv\
	\
		|_ Masks - Binary masks of gamma1 pedunculus region of the mushroom body for both the hemispheres. These were manually drawn using ImageJ Fiji software.\
			|_ Mask_2_plane1.tif\
			|_ Mask_5_plane1.tif\
\
		|_ Motion_corrected_tiff_files - masked motion corrected raw data, unmasked local pixel correlation image and maximum intensity projection of motion corrected movie.\
			|_ R1_plane1_correlation_image.tif\
			|_ R1_plane1_max_intensity_projection.tif\
			|_ R1_plane1_motion_corrected_masked.tif\
\
_________________________________________________________________________________________________________________________________________________________________________\
\
Jupyter notebooks description:\
\
1. ROI_fluorescence_trace_extraction_from_motion_corrected_tif_files_volume_imaging.ipynb\
	|_\
\
2. Universal_data_time_alignment_and_dFF_calculation.ipynb\
	|_\
\
3. Single_fly_dFF_response_plots_for_Sucrose_and_NHS.ipynb\
	|_\
\
4. Brainwise_time_binned_mean_std_median_dFF_response_of_regions_for_stimuli.ipynb\
	|_\
\
5. Sucrose_vs_NHS_mean_response_comparison_heatmap.ipynb\
	|_\
\
6. Sucrose_vs_NHS_mean_response_comparison_violin.ipynb\
	|_\
\
_________________________________________________________________________________________________________________________________________________________________________\
\
Metadata description:\
\
_________________________________________________________________________________________________________________________________________________________________________\
\
}
This repository contains data analysis and scientific investigation of the nebula IC 5146 (Cocoon) using the optical telescope TOBI. The primary objective of this project is to study the dust content within the nebula through multi-filter photometry.

    Ha_filter.ipynb, Hb_filter.ipynb, g_filter.ipynb, r_filter.ipynb, i_filter.ipynb
        Contains data reduction steps for five filters:
            Bias and Dark Subtraction: Removal of instrumental noise.
            Sky Subtraction: Correction for background light.
            Dithering Removal: Alignment of images for accurate photometry.

    bias&dark.ipynb
        Preparation of Master Bias and Master Dark frames for noise correction.

    calibration.ipynb
        Photometric calibration procedure to ensure accurate flux measurements.

    science.ipynb
        Scientific investigation of the dust content in IC 5146 using calibrated photometry.

    SNR.ipynb
        Analysis of Signal-to-Noise Ratio (SNR) and technical requirements necessary to achieve the scientific goals.

    concepts on telescopes detectors and photometry.pdf
        Theoretical background on telescopes, detectors, and photometric techniques.

    proposal_infurna.pdf
        Project proposal outlining the scientific goals, methodology, and expected outcomes.

    report_infurna.pdf
        Final report summarizing the findings and conclusions of the investigation.

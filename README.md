# Learning Relative Permeability Curve by Data Assimilation

The objective of this work is to infer the relative permeability curve kr(S) based on measurable data such as saturation and production time series. 

The proposed methodology is to use ensemble Kalman method, which has the advantage of being non-intrusive and parallel and does not need adjoint solver. The methodology is implemented by coupling the open-source framework for ensemble-based Data Assimilation & Field Inversion software: [DAFI](https://dafi.readthedocs.io/en/latest/) and open-source reservoir simulator: [OPM Flow](https://opm-project.org/?page_id=19).

### Framework
<img src="https://github.com/xuhuizhou-vt/KrCurve-Data-assimilation/blob/main/figs/Workflow.png" width="500">


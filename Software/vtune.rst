VTune
++++++

Introduction
============
Intel VTune profiler is a is a performance analysis tool for serial and multithreaded applications. 
Use VTune Profiler to analyze your choice of algorithm. Identify potential benefits for your application from available hardware resources.

Why VTune profiler is used?
---------------------------

* Helps to find most time-consuming (hot) functions in your application.
* To determine sections of code that do not effectively utilize available processor time.
* To identify whether your application is CPU or GPU bound and how effectively it offloads code to the GPU.


.. note::
    For installation check `installation methods <https://www.intel.com/content/www/us/en/docs/vtune-profiler/user-guide/2023-0/installation.html>`_ provided by Intel.
 
.. tip::
     For Linux OS following instructions can be followed for installation

code-block::javascript
    import React from 'react';
    import ReactDOM from 'react-dom/client';
    import './index.css';
    import App from './App';


    const root = ReactDOM.createRoot(document.getElementById('root'));
        root.render(
            <React.StrictMode>
                <App />
        </React.StrictMode>
            );


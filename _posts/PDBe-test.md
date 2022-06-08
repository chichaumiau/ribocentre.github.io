---
layout: post
title:  "VS ribozyme"
date:   2022-04-18T14:25:52-05:00
author: Chichau Miao
categories: ribozyme
---


<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
        <title>PDBe Mol* Helper Functions</title>
        
        <!-- Required for IE11 -->
        <script src="https://cdn.jsdelivr.net/npm/babel-polyfill/dist/polyfill.min.js"></script>
        <!-- Web component polyfill (only loads what it needs) -->
        <script src="https://cdn.jsdelivr.net/npm/@webcomponents/webcomponentsjs/webcomponents-lite.js" charset="utf-8"></script>
        <!-- Required to polyfill modern browsers as code is ES5 for IE... -->
        <script src="https://cdn.jsdelivr.net/npm/@webcomponents/webcomponentsjs/custom-elements-es5-adapter.js" charset="utf-8"></script>

        <link rel="stylesheet" type="text/css" href="https://www.ebi.ac.uk/pdbe/pdb-component-library/css/pdbe-molstar-3.0.0.css">
        <script type="text/javascript" src="https://www.ebi.ac.uk/pdbe/pdb-component-library/js/pdbe-molstar-component-3.0.0.js"></script>
        <style>
            #myViewer{
              float:left;
              width:400px;
              height: 400px;
              position:relative;
            }
        </style>
    </head>
    <body>

       
        <h4>PDBe Mol* Web-component Demo</h4>
  
        <!-- Molstar container -->
        <div id="myViewer">
            <pdbe-molstar id="pdbeMolstarComponent" molecule-id="2nnu" hide-controls="true"></pdbe-molstar>
        </div>
        
    </body>
</html>


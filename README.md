Angular2 pinch zoom directive.

## Installation

Install the npm package.

    npm i ngx-pinch-zoom
        
Import module:

    import { NgModule }         from '@angular/core';
    import { BrowserModule }    from '@angular/platform-browser';
    import { AppComponent }     from './app.component';
    import { PinchZoomDirective } from 'ngx-pinch-zoom/components';
     
    @NgModule({
        imports:      [ BrowserModule ],
        declarations: [ AppComponent, PinchZoomDirective ],
        bootstrap:    [ AppComponent ]
    })
    export class AppModule { } 

## Usage
    
    <div pinch-zoom>
        <img src="/assets/example.jpg" width="100%" />
    </div>

## Demo
http://crystalui.org/components/pinch-zoom/example
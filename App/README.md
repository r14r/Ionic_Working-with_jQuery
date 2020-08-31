# Working-with-jQuery
Working-with-jQuery


npm install jquery
npm install @types/jquery
import your page

import jQuery from "jquery";

Usage,

jQuery(".domElement").action();

---
import { Component, OnInit } from '@angular/core';
import { IonicPage } from 'ionic-angular';
import jQuery from "jquery";

@IonicPage()
@Component({
  selector: 'page-map',
  templateUrl: 'map.html',
})
export class MapPage implements OnInit{
  constructor(){ } 
  //Execute while opening
  ngOnInit() {
    jQuery("#modal").fadeOut();
  }

}

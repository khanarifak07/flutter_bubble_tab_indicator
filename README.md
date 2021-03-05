# Bubble Tab Indicator

[![pub package](https://img.shields.io/pub/v/bubble_tab_indicator.svg)](https://pub.dartlang.org/packages/bubble_tab_indicator)

A Flutter library to add bubble tab indicator to TabBar.

![banner](images/banner.jpg)

## Getting Started

Add package from github by adding the following to your pubspec.yaml, pub publication is added later.
````
  dependencies:
    bubble_tab_indicator: "^0.1.5"
````
Import the library in your file:
````
import 'package:bubble_tab_indicator/bubble_tab_indicator.dart';
````
Use the BubbleTabIndicator like this: 
````
new TabBar(
  indicatorSize: TabBarIndicatorSize.tab,
  indicator: BubbleTabIndicator(
            indicatorHeight: 25.0,
            indicatorColor: Colors.blueAccent,
            tabBarIndicatorSize: TabBarIndicatorSize.tab,
            // Other flags
            // indicatorRadius: 1,
            // insets: EdgeInsets.all(1),
            // padding: EdgeInsets.all(10)
          ),
)
````

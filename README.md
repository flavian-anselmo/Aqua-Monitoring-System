# Aqua-Monitoring-System
project requirements 
~~~dart
import 'dart:developer';

import 'package:flutter/material.dart';

void main() {
  runApp(
    const MyApp(),
  );
}

class MyApp extends StatelessWidget {
  const MyApp({
    Key? key,
  }) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      //debugShowCheckedModeBanner: false,
      home: Scaffold(
        body: GestureDetector(
          onTap: () {
         
            log("tapped");
          },
          child: Center(
            child: Image.asset("images/diamonds.jpeg"),
          ),
        ),
      ),
    );
  }
}

~~~

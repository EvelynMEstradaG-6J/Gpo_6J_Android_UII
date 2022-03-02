# Gpo_6J_Android_UII
Imágenes a utilizar en los proyectos de Flutter - UII.


import 'package:flutter/material.dart';

void main() => runApp(const TelmexApp());

class TelmexApp extends StatelessWidget {
  const TelmexApp({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    var tNegocio = 'IMG Red TELMEX - ESTRADA G.E.M. - 6J.';

    return MaterialApp(
      title: tNegocio,
      home: Scaffold(
        appBar: AppBar(
          title: Text(tNegocio),
        ),
        body: Image.network('https://c.tenor.com/gMUrkefHcdwAAAAC/seerlight-aesthetic.gif'),
      ),
    );
  }
}

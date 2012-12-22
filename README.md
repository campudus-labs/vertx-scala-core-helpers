vertx-scala-helpers
===================

Provides Vert.x helpers for Scala.

For Verticles, extend com.campudus.vertx.scala.deploy.Verticle.

For TestClasses, extend com.campudus.vertx.scala.framework.TestClientBase.

If you don't extend one of these classes, but still want to use the implicits, either extend the trait com.campudus.vertx.scala.VertxScalaHelpers or use import com.campudus.vertx.scala.VertxScalaHelpers._ to import the implicits from its companion object.
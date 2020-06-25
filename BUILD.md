Build for all scala versions
============================

sbt +package

Run tests for all scala versions
================================

sbt +test

Running a single test
=====================

sbt "test:testOnly *TypeLiteralSpec -- -z Primative"
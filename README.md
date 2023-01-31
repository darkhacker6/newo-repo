# newo-repo
مرحبًا ، هذا هو مستودعي الأول - في GitHub
سيتم إنشاء أدوات Linux و Termanix
steps:

- uses: actions/checkout@v3

- uses: actions/setup-java@v3

  with:

    distribution: 'temurin' # See 'Supported distributions' for available options

    java-version: '17'

- run: java HelloWorldApp.java

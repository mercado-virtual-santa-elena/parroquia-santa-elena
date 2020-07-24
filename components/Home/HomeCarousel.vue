<template>
  <div class="carousel relative container mx-auto bg-purple-100" style="max-width:1600px;">
    <div class="carousel-inner relative overflow-hidden w-full">
      <!--Slide 1-->
      <input
        class="carousel-open"
        type="radio"
        id="carousel-1"
        name="carousel"
        aria-hidden="true"
        hidden
        checked="checked"
      />
      <div class="carousel-item absolute opacity-0" style="height:475px">
        <div
          class="block h-full w-full mx-auto flex pt-24 md:pt-0 md:items-center bg-cover bg-right bg-purple-100"
        >
          <div class="container mx-auto">
            <div class="flex flex-col w-3/4 m-auto items-center px-auto tracking-wide">
              <p class="text-black text-lg my-4 text-center uppercase font-bold">
                Promover la
                <b class="text-yellow-600 text-xl">ayuda mutua</b> y el
                <b class="text-yellow-600 text-xl">consumo local</b> entre los
                hermanos de la Parroquia Santa Elena.
              </p>
              <div class="text-xl text-black uppercase border-t border-gray-600">Objetivo</div>
            </div>
          </div>
        </div>
      </div>
      <label
        for="carousel-4"
        class="prev control-1 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-gray-900 leading-tight text-center z-10 inset-y-0 left-0 my-auto"
      >‹</label>
      <label
        for="carousel-2"
        class="next control-1 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-gray-900 leading-tight text-center z-10 inset-y-0 right-0 my-auto"
      >›</label>

      <!--Slide 2-->
      <input
        class="carousel-open"
        type="radio"
        id="carousel-2"
        name="carousel"
        aria-hidden="true"
        hidden
      />
      <div class="carousel-item absolute opacity-0" style="height:475px">
        <div
          class="block h-full w-full mx-auto flex pt-24 md:pt-0 md:items-center bg-right bg-purple-100"
        >
          <div class="container mx-auto">
            <div class="flex flex-col w-3/4 m-auto items-center px-auto tracking-wide">
              <p class="text-black text-lg my-4 text-center uppercase font-bold">
                Facilitar la compra y
                venta de
                <b
                  class="text-yellow-600 text-xl"
                >productos</b> y
                <b class="text-yellow-600 text-xl">servicios</b>
                entre los hermanos de la Parroquia, sus familiares y contactos durante la pandemia del
                <b
                  class="text-yellow-600 text-xl"
                >covid-19</b>.
              </p>
              <div class="text-xl text-black uppercase border-t border-gray-600">Misión</div>
            </div>
          </div>
        </div>
      </div>
      <label
        for="carousel-1"
        class="prev control-2 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-gray-900 leading-tight text-center z-10 inset-y-0 left-0 my-auto"
      >‹</label>
      <label
        for="carousel-3"
        class="next control-2 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-gray-900 leading-tight text-center z-10 inset-y-0 right-0 my-auto"
      >›</label>

      <!--Slide 3-->
      <input
        class="carousel-open"
        type="radio"
        id="carousel-3"
        name="carousel"
        aria-hidden="true"
        hidden
      />
      <div class="carousel-item absolute opacity-0" style="height:475px;">
        <div
          class="block h-full w-full mx-auto flex pt-2 md:pt-0 md:items-center bg-right bg-purple-100"
        >
          <div class="container mx-auto">
            <div class="flex flex-col w-5/6 m-auto items-center px-auto tracking-wide">
              <p class="text-black my-4 text-center uppercase font-bold">
                Crear un espacio en línea
                donde se facilite la
                <b
                  class="text-yellow-600 text-lg"
                >promoción</b>
                de los productos y servicios que los hermanos miembros de las
                <b
                  class="text-yellow-600 text-lg"
                >
                  Pequeñas Comunidades
                  Parroquiales
                </b> ofrecen, como un medio que les ayude a incrementar sus ventas y
                satisfacer
                las necesidades de la feligresía, como ayuda mutua entre hermanos.
              </p>
              <div class="text-xl text-black uppercase border-t border-gray-600">Visión</div>
            </div>
          </div>
        </div>
      </div>
      <label
        for="carousel-2"
        class="prev control-3 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-gray-900 leading-tight text-center z-10 inset-y-0 left-0 my-auto"
      >‹</label>
      <label
        for="carousel-4"
        class="next control-3 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-gray-900 leading-tight text-center z-10 inset-y-0 right-0 my-auto"
      >›</label>

      <!--Slide 4-->
      <input
        class="carousel-open"
        type="radio"
        id="carousel-4"
        name="carousel"
        aria-hidden="true"
        hidden
      />
      <div class="carousel-item absolute opacity-0" style="height:475px;">
        <div
          class="block h-full w-full mx-auto flex pt-24 md:pt-0 md:items-center bg-right bg-purple-100"
        >
          <div class="container mx-auto">
            <div class="flex flex-col w-5/6 m-auto items-center px-auto tracking-wide">
              <p class="text-black my-4 text-center uppercase font-bold">
                Promover entre hermanos de la
                Parroquia la vivencia de
                los valores cristianos de
                <b
                  class="text-yellow-600 text-lg"
                >Ayuda mutua</b>,
                <b class="text-yellow-600 text-lg">Solidaridad</b>,
                <b class="text-yellow-600 text-lg">Honestidad</b>,
                <b class="text-yellow-600 text-lg">Justicia</b>,
                <b class="text-yellow-600 text-lg">Responsabilidad</b>.
              </p>
              <div class="text-xl text-black uppercase border-t border-gray-600">Valores</div>
            </div>
          </div>
        </div>
      </div>
      <label
        for="carousel-3"
        class="prev control-4 w-10 h-10 ml-2 md:ml-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-gray-900 leading-tight text-center z-10 inset-y-0 left-0 my-auto"
      >‹</label>
      <label
        for="carousel-1"
        class="next control-4 w-10 h-10 mr-2 md:mr-10 absolute cursor-pointer hidden text-3xl font-bold text-black hover:text-white rounded-full bg-white hover:bg-gray-900 leading-tight text-center z-10 inset-y-0 right-0 my-auto"
      >›</label>

      <!-- Add additional indicators for each slide-->
      <ol class="carousel-indicators">
        <li class="inline-block mr-3">
          <label
            for="carousel-1"
            class="carousel-bullet cursor-pointer block text-4xl text-gray-400 hover:text-gray-900"
          >•</label>
        </li>
        <li class="inline-block mr-3">
          <label
            for="carousel-2"
            class="carousel-bullet cursor-pointer block text-4xl text-gray-400 hover:text-gray-900"
          >•</label>
        </li>
        <li class="inline-block mr-3">
          <label
            for="carousel-3"
            class="carousel-bullet cursor-pointer block text-4xl text-gray-400 hover:text-gray-900"
          >•</label>
        </li>
        <li class="inline-block mr-3">
          <label
            for="carousel-4"
            class="carousel-bullet cursor-pointer block text-4xl text-gray-400 hover:text-gray-900"
          >•</label>
        </li>
      </ol>
    </div>
  </div>
</template>
<style>
.carousel-open:checked + .carousel-item {
  position: static;
  opacity: 100;
}

.carousel-item {
  -webkit-transition: opacity 0.6s ease-out;
  transition: opacity 0.6s ease-out;
}

#carousel-1:checked ~ .control-1,
#carousel-2:checked ~ .control-2,
#carousel-3:checked ~ .control-3,
#carousel-4:checked ~ .control-4 {
  display: block;
}

.carousel-indicators {
  list-style: none;
  margin: 0;
  padding: 0;
  position: absolute;
  bottom: 2%;
  left: 0;
  right: 0;
  text-align: center;
  z-index: 10;
}

#carousel-1:checked
  ~ .control-1
  ~ .carousel-indicators
  li:nth-child(1)
  .carousel-bullet,
#carousel-2:checked
  ~ .control-2
  ~ .carousel-indicators
  li:nth-child(2)
  .carousel-bullet,
#carousel-3:checked
  ~ .control-3
  ~ .carousel-indicators
  li:nth-child(3)
  .carousel-bullet,
#carousel-4:checked
  ~ .control-4
  ~ .carousel-indicators
  li:nth-child(4)
  .carousel-bullet {
  color: #000;
  /*Set to match the Tailwind colour you want the active one to be */
}
</style>
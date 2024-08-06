```bash
  /** @type {import('tailwindcss').Config} */
export default {
	content: ['./src/**/*.{astro,html,js,jsx,md,mdx,svelte,ts,tsx,vue}'],
	theme: {
		extend: {},
	},
	plugins: [],
}
```

## Instalamos las dependencias 
Ejecutamos el siguiente comando para instalar las dependencias si es que nos llega a faltar alguna

```sh
npm install
```


## Instalacion limpia
Si el módulo aún no se encuentra, puede que necesites limpiar el directorio node_modules e instalar las dependencias nuevamente

```sh
rm -rf node_modules
npm install

```

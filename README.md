<p align="center">
  <img src="assets/banner.gif" alt="banner" width="100%"/>
</p>

<h1 align="center">👋 Hi, I'm Vusk</h1>

<p align="center">
```C
/* ************************************************************************** */
/*                                                                            */
/*                                                        :::      ::::::::   */
/*   profil.c                                           :+:      :+:    :+:   */
/*                                                    +:+ +:+         +:+     */
/*   By: marudlof <marudlof@42.angouleme.fr>        +#+  +:+       +#+        */
/*                                                +#+#+#+#+#+   +#+           */
/*   Created: 1970/01/01 00:00:00 by unixstam          #+#    #+#             */
/*   Updated: 2026/10/26 13:20:08 by marudlof         ###   ########.fr       */
/*                                                                            */
/* ************************************************************************** */

#include <libft.h>
#include <ft_printf.h>
#include <fractol.h>
#include <minishell.h>
#include <miniRT.h>

typedef struct	s_profil
{
	char	*name;
	char	*school;
	int		age;
}				t_profil;

void	ft_print_profil(t_profil profil)
{
	ft_printf("My name is: %s\n", profil.name);
	ft_printf("I am %d years old \n", profil.age);
	ft_printf("I studied at: %s\n", profil.school);
}

int	main(void)
{
	t_profil	marudlof;

	ft_bzero(&marudlof, sizeof(t_profil));
	marudlof.name = "Mathis RUDLOFF";
	marudlof.age = 30;
	marudlof.school = "42 Angoulême";
	ft_print_profil(marudlof);

	return (0);
}
``` 
</p>

---

### 🧠 About me

- 💙 I **love the C language** and everything low-level

---

### 🛠️ Tech & Tools

<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/Shell-121011?style=for-the-badge&logo=gnu-bash&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vim-019733?style=for-the-badge&logo=vim&logoColor=white"/>
</p>

<!---
Vusk42/Vusk42 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

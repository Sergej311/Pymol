import pymol

def color_aa(arg1=None):
	acidic = 'resn ASP+GLU'
	basic = 'resn ARG+HIS+LYS'
	polar = 'resn SER+THR+ASN+GLN'
	special = 'resn CYS+GLY+PRO'
	hydrophobic = 'resn ALA+LEU+ILE+MET+PHE+TRP+TYR+VAL'

	cmd.color('grey', acidic)
	cmd.color('grey', basic)
	cmd.color('grey', polar)
	cmd.color('grey', special)
	cmd.color('orange', hydrophobic)
	util.cnc()

cmd.extend('caa', color_aa)
